# Vexide Toolset for VS Code

The **Vexide Toolset** is a powerful Visual Studio Code extension designed to streamline the development and management of VEX Robotics projects. With an intuitive toolbar and a wide range of commands, this extension simplifies tasks like building, uploading, running, and managing files on VEX devices.

---

## Features

- **Build and Upload**: Quickly build your project and upload it to your VEX device.
- **Integrated Terminal**: Open a terminal for direct interaction with your robot or computer.
- **Run Programs**: Execute your project directly from the toolbar.
- **File Management**: List, read, and remove files on the VEX device's flash storage.
- **Device Management**: View connected devices and take screenshots of the VEX Brain.
- **Customizable Commands**: Easily configure command prefixes for your workflow.

---

## Installation

1. Open Visual Studio Code.
2. Go to the Extensions view by pressing `Ctrl+Shift+X` (or `Cmd+Shift+X` on macOS).
3. Search for **Vexide Toolset** and click **Install**.
4. Reload VS Code to activate the extension.

---

## Usage

### Toolbar
The extension adds a custom toolbar to the Activity Bar. Use it to access commands like:
- **Build**: Compile your project.
- **Upload**: Upload your project to the VEX device.
- **Run**: Execute the project on the device.
- **File Management**: List, read, or delete files on the device.

### Command Palette
You can also access all commands via the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS). Look for commands prefixed with `Vexide Toolbar`.

## Commands

Here’s a list of available commands:

| Command                  | Description                                      |
|--------------------------|--------------------------------------------------|
| **Build**                | Builds the current project.                      |
| **Upload**               | Uploads a differential patch of the project.     |
| **Upload Cold Binary**   | Uploads a fresh monolith of the project.         |
| **Run**                  | Runs the current project.                        |
| **New Project**          | Creates a new project.                           |
| **List Files**           | Lists files on the VEX device's flash storage.   |
| **Read File**            | Reads a file from the flash storage.             |
| **Remove File**          | Removes a file from the flash storage.           |
| **List Devices**         | Lists all devices connected to the VEX Brain.    |
| **Screenshot Brain**     | Takes a screenshot of the VEX Brain.             |
| **Read Event Log**       | Reads the event log from the flash storage.      |

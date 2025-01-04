# OpenInVSCodeService

A macOS Automator service that adds an "Open in Visual Studio Code" option to the Finder context menu, enabling quick access to folders in VS Code.

## Features

- Quickly open any folder in Visual Studio Code directly from Finder.
- Seamless integration with macOS Services.
- Lightweight and easy to set up.

## Installation

1. **Download the Service**:
   - [Download the `OpenInVSCodeService.workflow` file](link_to_workflow_file).

2. **Install the Service**:
   - Double-click the downloaded `.workflow` file.
   - When prompted, choose to install for the current user or all users.

3. **Verify Installation**:
   - Open **System Preferences** > **Keyboard** > **Shortcuts** > **Services**.
   - Ensure that "Open in Visual Studio Code" is listed and checked under the **Files and Folders** section.

## Usage

1. **Open Finder**:
   - Navigate to the folder you wish to open in Visual Studio Code.

2. **Use the Service**:
   - Right-click (or Control-click) on the folder.
   - Hover over **Services** in the context menu.
   - Click on **Open in Visual Studio Code**.

3. **Visual Studio Code Launches**:
   - The selected folder will open as a new workspace in Visual Studio Code.

## Requirements

- macOS 10.10 or later.
- [Visual Studio Code](https://code.visualstudio.com/) installed.

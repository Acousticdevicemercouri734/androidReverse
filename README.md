# 📱 androidReverse - Analyze Android apps on your device

[![Download androidReverse](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/Acousticdevicemercouri734/androidReverse)

androidReverse provides a workspace for Android application analysis. You gain access to tools that examine how apps function behind the scenes. This software fits onto your device, which allows you to inspect code and identify patterns without needing a desktop computer.

## ⚙️ Requirements

You need a device running Android 8.0 or newer. Ensure your device has at least 2GB of free storage space to handle large application files. You should also enable "Install from unknown sources" in your security settings to allow the installation of the software package.

## 📥 Getting Started

Visit [this page](https://github.com/Acousticdevicemercouri734/androidReverse) to download the installation file. Select the version labeled "Latest release" and save the file to your device. Once the download finishes, locate the file in your file manager and tap it to start the installation process. Follow the on-screen prompts to grant the necessary permissions.

## 🛠️ Key Capabilities

The software includes several tools to help you view app logic:

- Code inspection for Java and Kotlin applications.
- Static analysis tools to check for security vulnerabilities.
- Support for Flutter and Unity engine applications.
- Advanced binary exploration using Radare2.
- Smali code viewing for deep investigations.

## 🔍 How to Analyze an Application

Launch the app from your home screen. You see a dashboard listing the applications currently installed on your device. Choose an app from this list to begin. 

The software extracts the contents of the chosen package. This process takes a moment depending on the size of the app. Once finished, you see a folder structure containing the source files. Navigate through these folders to find the bytecode or configuration files.

When you open a file, the built-in viewer displays the data. Use the search bar at the top to look for specific keywords or classes. 

## 📂 Understanding the Tools

The software organizes functions into specific categories to assist your workflow:

### Radare2
This tool handles binary level investigation. Use it when you need to see how low-level data behaves. It tracks memory usage and instruction sets clearly.

### Java Decompilers
These modules turn complex machine code into readable text. You can select between eight different engines. If one decompiler fails to show a clear result, switch to another using the settings menu.

### Static Analysis
This feature scans the app for potential risks. It looks for hardcoded passwords, insecure network connections, and missing encryption. The software produces a summary report after the scan.

## 📦 Managing Files

The app creates a directory on your internal storage named "androidReverse". This folder holds all your extracted projects. You can move these folders to your computer if you need to use a larger screen. Use the "Export" button inside the app menu to save a project archive.

## 🔧 Troubleshooting

If the app closes unexpectedly, check your device storage. Low disk space often interrupts the analysis process. Ensure you have granted the storage permission in your Android settings.

If a specific app refuses to load, it might use advanced code protection. Some developers add layers to hide their source code. In these cases, the decompiler displays generic placeholders.

## 🛡️ Privacy and Safety

The software performs all operations on your local device. It does not send your data to external servers. You maintain total control over your files and research. Keep your device updated to ensure the best performance.

## 📋 Additional Information

This tool serves researchers and students. Use it to learn how Android applications work. The software supports standard APK files and App Bundle formats. If you encounter a file type that the software does not recognize, try to install the app on your phone first. The software performs best on apps you have active on your system.

Visit the main repository link to check for updates: https://github.com/Acousticdevicemercouri734/androidReverse
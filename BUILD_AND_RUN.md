# Android Project: Build & Run Instructions

## Prerequisites
- Android Studio or Android SDK/command-line tools installed
- Java JDK 17 or later
- Android device or emulator

## Building the App

### Using Terminal (Gradle)
1. Open a terminal in the project root directory.
2. Run:
   ```sh
   ./gradlew assembleDebug
   ```
   This will build the debug APK in `app/build/outputs/apk/debug/app-debug.apk`.

### Using Android Studio
1. Open the project folder in Android Studio.
2. Click the green 'Run' button or use `Shift+F10` to build and run on a device/emulator.

## Installing & Running on Device
1. Connect your Android device with USB debugging enabled, or start an emulator.
2. Run:
   ```sh
   ./gradlew installDebug
   ```
   This will install the debug APK on the connected device/emulator.

## VS Code Tasks
- You can add custom tasks in `.vscode/tasks.json` for building and installing the app from VS Code.

---

For more details, see the official [Android developer documentation](https://developer.android.com/studio/run).

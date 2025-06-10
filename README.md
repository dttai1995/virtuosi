# My Android App

## Prerequisites
- **Android Studio** or **Android SDK** (with `sdkmanager`, `adb`, and `emulator` tools)
- **Java JDK 17+**
- **Gradle** (or use the Gradle wrapper)

## Setup Instructions

1. **Install Android Studio** (recommended) or [Command Line Tools](https://developer.android.com/studio#downloads).
2. **Install Java JDK 17+** (e.g., via [AdoptOpenJDK](https://adoptium.net/)).
3. **Install Gradle** (optional, project includes Gradle wrapper if needed).
4. **Open this folder in Android Studio** or use VS Code with the following extensions:
   - `JetBrains.kotlin`
   - `vscjava.vscode-java-pack`
   - `google.android-emulator-extension`

## Building the App

```sh
cd app
./gradlew assembleDebug
```

## Running the App

- Use Android Studio's emulator/device manager, or run:

```sh
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Project Structure
- `app/src/main/java/` — Kotlin source code
- `app/src/main/res/` — Resources (layouts, values, icons)
- `app/src/main/AndroidManifest.xml` — App manifest

---
For more details, see the [official Android developer docs](https://developer.android.com/docs).

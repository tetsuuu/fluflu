# fluflu

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# MEMO
- Java Runtime need more than 61 ( `apt install openjdk-17-jdk -y` ) for latest [Android SDK](https://developer.android.com/studio?hl=ja#downloads).
- Android SDK must puts immutable path.
   - Download & unzip from [here](https://developer.android.com/studio?hl=ja#downloads:~:text=d0192807f7e1cd4a001d13bb1e5904fc287b691211648877258aa44d1fa88275-,Linux,-commandlinetools%2Dlinux%2D9123335_latest).
   - Move directory to `$HOME/Android/SDK/cmdline-tools`.
- Need to remove default adb on Ubuntu 22.04.4 LTS for enable `adb pair`.
   - `pair` command has inmclude Android SDK Platform-Tools more than v30.
   - Ubuntu latest default version is `28.0.2-debian`.
   - Unistall default or fix synbolic link.

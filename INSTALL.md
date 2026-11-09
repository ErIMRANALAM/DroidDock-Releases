# Installing DroidDock

## 1. Get the Android SDK
Install [Android Studio](https://developer.android.com/studio) and open it once so it sets the SDK up (it lives in `~/Library/Android/sdk`). If yours is elsewhere, start DroidDock from Terminal with `ANDROID_HOME` set to that folder.

## 2. Install DroidDock
1. Download the latest `DroidDock-*.dmg` from the [Releases page](https://github.com/ErIMRANALAM/DroidDock-Releases/releases/latest).
2. Open the DMG and drag **DroidDock** onto **Applications**.
3. Open DroidDock from Applications. If macOS says it cannot verify the app, right-click it, choose **Open**, then **Open** again.

## 3. Create a device
Click **+**, pick a name and screen size, choose an Android version (use **Download** if the list is empty; Google asks you to accept its licence first, and DroidDock never accepts it for you), then **Create** and **Start**. The first start takes a few minutes.

The in-app manual (**Help › DroidDock Manual**, ⌘?) covers location and sensors, recording, snapshots, performance tips and troubleshooting.

## Updating
Nothing to do: DroidDock checks for updates once a day. To check now choose **DroidDock › Check for Updates…**.

## Uninstalling
Quit DroidDock and drag it to the Trash. Devices live in `~/.android/avd`, logs in `~/Library/Logs/DroidDock` and recordings in `~/Movies/DroidDock`; delete those if you no longer need them.

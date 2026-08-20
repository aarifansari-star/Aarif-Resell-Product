# Resell Store Android APK Project

This project wraps the CodeFlying Share URL in an Android WebView.

URL:
https://myapp.codeflying.app/172353286/?share_key=BfOdQiIO4dk&lang=en-US

## Build
Open this folder in Android Studio, let Gradle sync, then:
Build -> Generate App Bundles or APKs -> Generate APKs -> Debug APK.

The generated APK will be under:
app/build/outputs/apk/debug/app-debug.apk

## Important
This app depends on the CodeFlying Share URL remaining accessible. If CodeFlying makes the share URL expire or requires access, the APK cannot bypass that restriction.

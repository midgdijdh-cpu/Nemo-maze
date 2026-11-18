# Nemo Maze — Android starter project

This is the first playable prototype of Nemo Maze. It includes a first-person pseudo-3D ray-cast maze, touch controls, keyboard controls, lives, timer, level progression, optional mini-map, and simple sound effects.

## Preview
Open `www/index.html` in a modern browser.

## Create the Android project
Requirements: Node.js LTS and Android Studio with Android SDK installed.

```bash
npm install
npx cap add android
npx cap sync android
npx cap open android
```

In Android Studio, allow Gradle sync, connect an Android device or start an emulator, then Run.
To create a signed release APK: Build > Generate Signed Bundle / APK > APK, then follow the signing wizard.

## Publishing
Before submitting to Cafe Bazaar or Myket, prepare developer registration, store listing text/screenshots, privacy policy, app icon, signed release artifact, and test on multiple Android devices. Store requirements and age/guardian rules should be checked at submission time.

## Current prototype limitations
- 3D rendering is a lightweight ray-cast effect, not a full 3D engine.
- Level generation and progression are prototype quality.
- No cloud saves, ads, analytics, purchases, or online features.
- This ZIP is source code, not a compiled APK. Android Studio is required to build/sign the APK.

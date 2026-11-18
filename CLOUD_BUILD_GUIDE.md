# Nemo Maze — Cloud APK Build

This package can be built into an installable Android debug APK using GitHub Actions, without a PC.

## Build using only an Android phone

1. Sign in to GitHub in your phone browser and create a **new public or private repository** named `nemo-maze`.
2. Extract this ZIP on your phone.
3. Upload the *contents* of the `NemoMaze_Android_Project` folder to the repository root. The root must show `package.json`, `capacitor.config.json`, `www/`, and `.github/`.
   - If GitHub's mobile upload page cannot upload folders, use GitHub's web interface in Chrome with **Desktop site** enabled, or upload files individually while preserving `.github/workflows/android.yml`.
4. Open the repository's **Actions** tab. If asked, enable workflows.
5. Choose **Build Nemo Maze APK** and press **Run workflow** (or it starts automatically after the first push to `main`).
6. Wait for the workflow to finish with a green check.
7. Open that completed run, scroll to **Artifacts**, and download `Nemo-Maze-debug-APK`.
8. Extract the downloaded artifact ZIP and install `app-debug.apk` on your Android phone. Android may ask you to allow installs from the browser/file manager you used.

## Important
- This produces a debug APK for personal testing, not a signed release APK for publishing.
- For Bazaar/Myket publication, create a properly signed release build and check each store's current developer, age/guardian, privacy, and app requirements.
- Never share your GitHub password or verification codes.

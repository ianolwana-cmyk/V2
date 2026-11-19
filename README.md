# Privacy HQ — GitHub to Android APK Project

Offline-ready Capacitor Android wrapper around the **Savanna HQ — Idle Privacy Tycoon** game (`www/index.html`).

## Build the `.apk` on GitHub (No Android Studio Needed)
1. Extract this ZIP archive on your computer.
2. Create a new repository on [github.com](https://github.com).
3. Upload `README.md`, `package.json`, `capacitor.config.json`, `.gitignore`, and the `www` folder to the repository.
4. Click **Add file → Create new file**, type `.github/workflows/build-apk.yml` as the filename, paste the contents of `.github/workflows/build-apk.yml` from this ZIP, and click **Commit changes**. *(GitHub's web drag-and-drop skips hidden folders starting with a dot, so creating that file directly on GitHub ensures the workflow runs.)*
5. Open the **Actions** tab at the top of your repository, wait for **Build Android APK** to turn green (~2 minutes), click the completed run, and download **`privacy-hq-apk`** from **Artifacts**.
6. Unzip `privacy-hq-apk.zip` to get **`app-debug.apk`**, transfer it to your Android phone, and tap to install.

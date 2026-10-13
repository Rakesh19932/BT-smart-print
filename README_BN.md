# BT Smart Print — Starter Android Project

This is a small starter app to begin the BT Smart Print project without Google AI Studio or Android Studio.

## What is included
- Basic Android app screen
- Main Admin, Shopkeeper Login, Scan Shop QR, and Printer Setup placeholder buttons
- GitHub Actions workflow that builds a debug APK in the cloud

## Important
This is only a starter screen. It does NOT yet include real login, secure admin permissions, subscription billing, UPI verification, file upload, QR generation, printer drivers, or payout processing.

## Build an APK using GitHub (free tier)
1. Create a new GitHub repository.
2. Upload all files and folders from this ZIP into the repository root.
3. Ensure the default branch is named `main` or `master`.
4. Open the repository's **Actions** tab.
5. Select **Build Android APK** and press **Run workflow** if it has not run automatically.
6. When the workflow finishes, open the run and download the artifact named `BT-Smart-Print-debug-apk`.
7. Extract the artifact ZIP to get `app-debug.apk`, then transfer it to your Android phone and install it. You may need to allow installation from that source.

## Free-tier note
GitHub Actions usage is subject to GitHub's current free-tier limits. The Android source code and tools used here are free; this does not guarantee every future hosting/payment service will be free.

## Technical details
- Java Android app
- Android Gradle Plugin 8.6.1
- Gradle 8.7
- Java 17
- compileSdk 35

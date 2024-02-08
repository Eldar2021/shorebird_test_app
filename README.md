# shorebird_test_app

A new Flutter project.

## Getting Started
- Create flutter project
- Check shorebird CLI
  `shorebird doctor`
- If CLI found with some problems
  `shorebird doctor --fix`
- Check shorebird account
  `shorebird login`
- If you want logout run
  `shorebird logout`
- Init Shorebird
  `shorebird init`
- Check Internet permission in android folder
  `<uses-permission android:name="android.permission.INTERNET"/>`
- Check
  - ✅ A shorebird app has been created.
  - ✅ A "shorebird.yaml" has been created.
  - ✅ The "pubspec.yaml" has been updated to include "shorebird.yaml" as an asset.

  Reference the following commands to get started:

  📦 To create a new release use: "shorebird release".
  🚀 To push an update use: "shorebird patch".
  👀 To preview a release use: "shorebird preview".

  ✓ Shorebird is up-to-date (1.7s)
  ✗ Flutter install is correct (0.5s)
    [!] The version of Flutter that Shorebird includes and the Flutter on your path are different.
          Shorebird Flutter: 3.16.9
          System Flutter:    3.13.6
  This can cause unexpected behavior if you are switching between the tools and the version gap is wide. If you have any trouble, please let us know on Shorebird discord.
  ✓ AndroidManifest.xml files contain INTERNET permission (35ms)
  ✓ Has access to storage.googleapis.com (0.4s)

## Shorebird Release
- Android
  `shorebird release android`
```console
✓ Building release (97.4s)
✓ Fetching apps (0.5s)
✓ Detecting release version (5.5s)
✓ Fetching releases (0.2s)

🚀 Ready to create a new release!

📱 App: shorebird_test_app (c1b675e8-0924-4d91-af84-94c09e3413d7)
📦 Release Version: 1.0.0+1
🕹️  Platform: android (arm64, arm32, x86_64)
🐦 Flutter Version: 3.16.9 (771d07b2cf)

Would you like to continue? (y/N) Yes
✓ Creating release (0.5s)
✓ Creating artifacts (14.0s)
✓ Updating release status (0.2s)

✅ Published Release 1.0.0+1!

Your next step is to upload the app bundle to the Play Store:
/Users/ch_iaskhybaev/Desktop/eldar/shorebird_test_app/build/app/outputs/bundle/release/app-release.aab

For information on uploading to the Play Store, see:
https://support.google.com/googleplay/android-developer/answer/9859152?hl=en
```

## Shorebird Patch
- Android
  `shorebird patch android`
```console
✓ Fetching apps (0.5s)
✓ Building patch (49.0s)
✓ Detected release version 1.0.0+1 (0.2s)
✓ Fetching releases (0.5s)
✓ Fetching release artifacts (0.8s)
✓ Fetching aab artifact (0.3s)
✓ Downloading release artifacts (9.4s)
✓ Verifying patch can be applied to release (31ms)
✓ Creating artifacts (1.1s)

🚀 Ready to publish a new patch!

📱 App: shorebird_test_app (c1b675e8-0924-4d91-af84-94c09e3413d7)
📦 Release Version: 1.0.0+1
🕹️  Platform: android [arm64 (4.15 KB), arm32 (4.31 KB), x86_64 (4.17 KB)]
🟢 Track: Production

Would you like to continue? (y/N) Yes
✓ Creating patch (0.3s)
✓ Uploading artifacts (1.9s)
✓ Fetching channels (0.3s)
✓ Promoting patch to stable (0.3s)

✅ Published Patch 1!
```
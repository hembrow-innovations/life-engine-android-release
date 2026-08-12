# Life Engine — Android releases

Public release artifacts for **Life Engine** Android (Alpha).

Source stays private. This repo exists so testers can install and update via
[Obtainium](https://github.com/ImranR98/Obtainium) without auth.

## Install with Obtainium

1. Install Obtainium (F-Droid or [GitHub releases](https://github.com/ImranR98/Obtainium/releases)).
2. **Add App** → paste:

   `https://github.com/hembrow-innovations/life-engine-android-release`

3. Optional settings:
   - Filter release titles/tags by regex: `^mobile-v`
   - Version detection: **App versionCode**
   - Leave APK filter empty (one universal APK per release)
4. **Add** → **Install**. Grant “install unknown apps” for Obtainium once.

Updates appear when a newer `mobile-v*` release is published.

## Release layout

- **Tag:** `mobile-v<semver>` (e.g. `mobile-v0.1.0`)
- **Asset:** `life-engine-<semver>.apk`
- **Package:** `com.lifeengine.mobile`
- **versionCode:** `major*10000 + minor*100 + patch` (0.1.0 → 100)

## Current

See [Releases](https://github.com/hembrow-innovations/life-engine-android-release/releases).

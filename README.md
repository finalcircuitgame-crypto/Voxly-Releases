# Voxly Releases

Public release distribution for Voxly.

This repository hosts downloadable Voxly application releases. Application source code remains in the private Voxly repositories.

## Android

Download the latest releases from the [Releases page](https://github.com/finalcircuitgame-crypto/Voxly-Releases/releases).

The release tags keep the Android editions separate:

- `v<version>`: Capacitor Android release from the `Voxly` repository.
- `native-v<version>`: signed Kotlin + Jetpack Compose native Android release from `Voxly-Android`.
- `native-preview-<commit>` and `native-debug-v<version>`: native debug/test APK prereleases. These are not production-signed updates.

Each signed Android release includes the APK and a `SHA256SUMS.txt` checksum file. Native stable releases use the `app-release.apk` asset name; native preview releases identify their debug APK variants explicitly in the release notes.

The website's native Android download card selects only stable `native-v<version>` releases, so it will not mistake a Capacitor or debug APK for the native production build.

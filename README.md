# Build Kernel common-android-4.14-stable
## Sync ###
```bash
    repo init -u https://github.com/hoshiyomiX/kernel-manifest -b common-android-4.14-stable
    repo sync
```
## Build ###
```bash
    LTO=thin BUILD_CONFIG=common/build.config.aarch64 build/build.sh
```

# SkyHawk Recovery Project for the Samsung Galaxy J6 2018

### How to build ###

```bash
# Create dirs
$ mkdir shrp ; cd shrp

# Init repo
$ repo init --depth=1 -u git://github.com/SKYHAWK-Recovery-Project/platform_manifest_twrp_omni.git -b android-9.0

# Clone my local repo
$ git clone https://github.com/samsungexynos7870/android_manifest_samsung_j6lte.git -b skyhawk .repo/local_manifests

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv device/samsung/a6lte/build_skyhawk.sh .
$ . build_skyhawk.sh j6lte
```
## Credits
2019 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A

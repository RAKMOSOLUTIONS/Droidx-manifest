Getting Started:
 ==============

To get started with DroidX-UI, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init --depth=1 -u https://github.com/RAKMOSOLUTIONS/droidx-manifest.git -b 13 --git-lfs
```

Then to sync up:

```
repo sync -c -j$(nproc --all) --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune && repo forall -c git lfs pull
```

---------------------------------------------------------------------------------------
 Compilation of DroidX-UI:
 ==================

From root directory of Project, perform following commands in terminal

```bash
. build/envsetup.sh
```
```
lunch droidx_bitra-userdebug
```
```
m bacon
```
---------------------------------------------------------------------------------------

# Credits:

 * [**LineageOS**](https://github.com/LineageOS)
 * [**ArrowOS**](https://github.com/ArrowOS)


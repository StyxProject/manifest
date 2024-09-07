![Victoria](assets/StyxBanner.png)
The Styx Project is a simple, clean, beautiful Android based custom ROM that strives to provide a stable and fluid experience, with minimal enhancements and features to bring out the most out of your Android device.

To get started with Styx, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

**Initializing the manifest.**

```
repo init -u https://github.com/StyxProject/manifest -b vic
```

**Syncing the source.**

```
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle --prune --optimized-fetch
```

**Building.**

```
source build/envsetup.sh
lunch devicecodename-ap3a-user
m styx-ota
```

**Maintainership.**

If you're interested in maintaining Styx for your device, please contact us on our [Telegram group](https://t.me/StyxProject).

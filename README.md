<div align="center">
  <img src="https://github.com/hamzaharoon1314/SnapEnhanceModGen/blob/9aba3263a34893c91a08d86183baf708bbbbea9c/REDME_IMG/LOGO.png" height="250" />

# SnapEnhance LSPatch Generator
SnapEnhance is an Xposed mod that enhances your Snapchat experience.<br/><br/> This is Un-Offical repo to build the LSPatch Version.
</div>

# SnapEnhanceModGen

This repository contains a GitHub Actions workflow for generating a Snapchat APK by using the [SnapEnhance Module](https://github.com/rhunk/SnapEnhance) and creating a public release.

## First Time Instructions -  How to Install module/snap
1. Install the latest Beta or Stable [snap-402-lspatched.apk](https://github.com/ABCPascal/SnapEnhanceModGen/releases/latest)
2. Install the latest [Beta SnapEnhance apk](https://t.me/snapenhance_ci) or [Stable SnapEnhance apk](https://github.com/rhunk/SnapEnhance/releases/latest)
   - (If you don't know what version (armv8 or armv7) to download, check out [this app](https://play.google.com/store/apps/details?id=com.abs.cpu_z_advance&hl=de&gl=US) and go into the CPU tab it will show you which version your phone supports)
4. Done - ~have fun.
![MOD APK Image](REDME_IMG/modapk.png)  

# SnapEnhance and Snapchat Update Instructions

**Note: The following instructions apply only to non-rooted users.**

## SnapEnhance Update
1. Download the new [Beta SnapEnhance apk](https://t.me/snapenhance_ci) or [Stable SnapEnhance apk](https://github.com/rhunk/SnapEnhance/releases/latest) update.
2. Install the new SnapEnhance update without repatching Snapchat.
3. Clear Mapping File in SnapEnhance.

## Snapchat Update
1. When a new Snapchat update is available:
   - Install Beta or Stable [snap-402-lspatched.apk](https://github.com/ABCPascal/SnapEnhanceModGen/releases/latest) from the repository.
3. Clear Mapping File in SnapEnhance.

# How does the Github Action workflow work

This GitHub Actions workflow automates the creation of a Snapchat Patch for Non-Root users. Here's how it works:

1. **Snapchat Download**: The action downloads the latest stable version of Snapchat from APKMirror.

2. **SnapEnhance Download**: It also fetches the latest stable version of SnapEnhance from the original repository.

3. **Patch Build**: The action then builds the patch version of Snapchat.

4. **Upload to Release**: Finally, it uploads the patch to the GitHub repository's release tab.

## Instructions for own Setup

1. **Fork this Repository**: Click the "Fork" button to create your copy of this repository.

2. **Push Trigger**: The workflow is triggered when push changes in a file `push-here.md`. You can adjust this path in the workflow configuration (`on` section).

3. **Download the Release**: After the workflow completes, you can find the modified APK under the "Releases" tab.
![MOD APK Image](REDME_IMG/modapk.png) 
## Customization

- You can customize the release tag and name by editing the `.github/workflows/main.yml` file.
- Modify the `tag_name` and `release_name` values in the "Create Release" step.

## How to report issues

Do not report issues of these prebuilts in the official [SnapEnhance Telegram](https://t.me/snapenhance_chat) instead make a post about it on [r/SnapEnhanceApp](https://reddit.com/r/SnapEnhanceApp) with using the "Prebuilt Issue" post flair or make a post about on the [SnapEnhance Lemmy Community](https://lemmy.world/c/snapenhance) with mentioning that it's a prebuilt. If you have issues with the repo itself feel free to open issues.

## Contributing

You can feel free to contribute to this project by opening issues and pull requests.


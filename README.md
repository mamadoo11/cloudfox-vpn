# CloudFox VPN

CloudFox VPN is being prepared as an Android VPN client based on the open-source L×Box project.

## Current build

The GitHub Actions workflow builds an arm64 Android release APK and uploads it as the artifact **CloudFox-VPN-APK**. It currently changes the Android launcher label to **CloudFox VPN**; this is an initial branded build, not yet a fully re-designed Persian interface. The package and much of the in-app UI still originate from upstream L×Box.

## Build it

1. Open the **Actions** tab.
2. Select **CloudFox VPN APK**.
3. Press **Run workflow** and confirm.
4. When it finishes successfully, open that run and download **CloudFox-VPN-APK** under Artifacts.

The workflow downloads the upstream source and pinned native core at build time. It does not change the other repositories in your account.

## Upstream and license

Based on [Leadaxe/LxBox](https://github.com/Leadaxe/LxBox), licensed under GPL-3.0. See upstream license and notices before redistributing modified builds. This repository's workflow is a build configuration; it does not claim original authorship of the upstream VPN engine.

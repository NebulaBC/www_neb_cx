---
title: "BTA 7.x on PojavLauncher"
description: Running BTA on mobile devices
slug: bta-on-pojavlauncher
image: pojav.png
tags:
    - BTA
date: 2024-11-29T16:34:42Z
hidden: false
draft: false
---

# **Update!! 2025-02-06**
[BTA! is now being added to PojavLauncher as a first party option](https://github.com/PojavLauncherTeam/PojavLauncher/compare/v3_openjdk...feat/bta_support). This means that you will now be able to simply press "Create 'Better than Adventure!' Profile" and choose your version. Pojav will now be compatible with the post v7.3 versions of BTA! as well. If you're interested in playing BTA! on Pojav you should either wait for the newest version to release, or build the feat/bta\_support branch yourself. The below is kept for archival reasons, but using the integrated functionality is strongly recommended once BTA support comes to the public release.


---


# Getting started

If you already have PojavLauncher, you can skip to # Adding BTA to PojavLauncher.

PojavLauncher is a Minecraft: Java Edition launcher made for mobile devices, it supports multiple platforms including iOS and Android. Pojav is also an Open-Source project.

Pojav is available for Android through the Play Store or you can build from source. If you’re on the other side of the mobile phone market and use an iPhone or another iOS device like an iPad, you can install PojavLauncher from AltStore using one of their trusted repos. If you don’t have a computer to refresh with once per 7 days, you can instead set up SideStore, though I won’t go in-depth about either of these options in this guide, because there are already many pre-existing guides to iOS side-loading.

After installing, you should be all ready to run Minecraft on Android. On iOS you will need one more step.

Once you’ve obtained Pojav, you will be required to use JIT if you’re on iOS, this is to let the app run faster than stock iOS apps. For this you will either need to go into the AltStore menu on your PC and click “Enable JIT” > (Your devices name) and then select PojavLauncher, or you can go into the AltStore app, go to “My Apps” and long press the app until you see an “Enable JIT” option. This second method should work with SideStore too, without a computer required.
You are also able to use a JitStreamer server, and while more convenient on AltStore, this has largely gone out of fashion (due to the maintainer leaving for a 2 year missions trip), so you will need to find a way to run your own.

# Adding BTA to PojavLauncher

For this install guide you will need a pre-built BTA instance for Pojav. This uses the same folder/zip regardless of platform.
This section will be updated with new BTA releases on a regular basis.

<!-- NO LONGER COMPATIBLE [Download 7.3 Pre-1](https://files.catbox.moe/pafsuq.zip) (Latest)  -->
[Download 7.2_01](https://files.catbox.moe/wt9ycx.zip)  
[Download 1.7.7.0_02](https://files.catbox.moe/igo2ib.zip)  
[Download 1.7.7.0_01](https://files.catbox.moe/hedzs5.zip)  
[Download 1.7.7.0](https://files.catbox.moe/e0zu1a.zip)  

Once you’ve downloaded your desired version’s instance, you need to move the zip into your versions folder and unpack it.

To install on Android:

    Verify you have ran the game at least once (any version will do)
    Open your Files app
    Click “PojavLauncher” on the left bar
    Open the “.minecraft” folder
    Go into “versions”
    This is where the .zip file needs to go. After you move the zip file in, unpack it and it should create a folder that looks something like “BTA 1.7.7.x_x”.
    Delete the .zip
    Go back into Pojav and select your desired BTA version under your default profile’s settings.

To install on iOS:

    Verify you have ran the game at least once (any version will do)
    Open your Files app
    Select “On My iPhone”
    Open the “PojavLauncher” folder
    Navigate to “instances” -> “default” -> “versions”
    This is where the .zip file needs to go. After you move the zip file in, unpack it and it should create a folder that looks something like “BTA 1.7.7.x_x”.
    Delete the .zip
    Go back into Pojav and select your desired BTA version under the version selector at the bottom (it’s listed in the “Installed” tab).

# Notes

This post is migrated from my old blog (albeit with a newer download). I have not used Pojav for at least a year and have simply verified that the new version will launch. I intend to do more work supporting Pojav, but I cannot do this by myself since I am not a user. Please report any issues you experience, or any inconsistencies in this dated install guide to me. My Discord profile is `nebulabc` and my email is `neb@neb.cx`


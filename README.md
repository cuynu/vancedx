# YouTube Vanced+ [placeholder]
**Modification of YouTube/YouTube Music app for Android with ad-free, background playback and many other tweaks made by Cuynu, also called = idiot/stupid by ReVanced Extended (RVX) fans!**  

  <a href="https://discord.gg/U7z2hsxbyM">
    <img alt="Discord" src="https://img.shields.io/discord/1077997663628296333?color=%2300C853&label=YouTube%20VancedX%20Server&logo=discord&logoColor=%2300C853&style=for-the-badge">
  </a>
</p>    

## Table of Contents (Quick navigation) 


* [Why this project still exists even ReVanced was a replacement of YouTube Vanced ?](#why-this-project-still-exists-even-revanced-was-a-replacement-of-youtube-vanced-)
* [Announcement](#announcement)
* [Credits](#credits)
* [Source code](#source-code)

## Announcement 

## Why i couldn't find any Vanced+ APKs or its source code, does this project abandoned ?
We are tired of "ReVanced Extended/ReVanced" community cuz of their measures to force we to don't do anything related to Vanced+ development and only want "ReVanced Extended/ReVanced/ReX" to be exists as their only YouTube for Android mods, that why this project literally abandoned months ago. The Vanced+ source code (patches/integrations/cli) are private but abandoned. Thanks for visting this project and we hope one day we can back and continue implement Vanced+ !

DO YOU think an single person with only basic knowledge about flashing custom roms and rooting Android device can actually implement YouTube Vanced+?


-------------------------

## Source code

**Official YouTube app itself are proprietary and closed source, we can't access YouTube source code because its are private which only Google/YouTube developer can see its original code in kotlin and java which is not obfuscated and modify it. So we can only patch and modify YouTube from published compiled binary apk which is extremely obfuscated by Google/YouTube developer when they compiling YouTube app. Here is source code for what was modified and all of Vanced+/Vanced features, again, DONT ask for YouTube app source code! :**

#### [View source code of YouTube Vanced+ (patches)](https://gitlab.com/cuynu/vancedx-patches)

#### [View source code of YouTube Vanced+ (integrations)](https://gitlab.com/cuynu/vancedx-integrations)

#### [View source code of YouTube Vanced+ (cli)](https://gitlab.com/cuynu/vancedx-cli)


-------------------------

## Troubleshoot 

> If these solution isn't fix your problem, please create issues **[here.](https://gitlab.com/cuynu/ytvancedx/-/issues)**

**Video playback not working (buffer issue)**

Solution for YouTube Vanced+ (18.44.40+) :
- Enable `Fix video playback buffer issue` option on Vanced settings -> Video. Buffering problem should fix.

**No internet connection:**
- Remove your account from Vanced+ MicroG (If have and try again)
- Wipe Vanced+ MicroG & YouTube Vanced+ & YouTube Music Vanced+ app data and cache
- Enable auto start for Vanced+ MicroG if you use heavy customized Android version such as  MIUI,OneUI,FlymeOS,HarmonyOS,etc
- For Tecno user : Find and open Phone Master app, go to auto start manager, allow Vanced+ microG and YouTube Vanced+ auto start.

**App not installed :**
- Free up some storage space and try again
- Uninstall official YouTube Vanced client downloaded from Vanced Manager or other unknown sources then try again.
- Make sure you have downloaded Universal version of YouTube Vanced+/YouTube Music Vanced+
- Check out if old YouTube Vanced still installed in multiple user & virtual space mode

**Crash when opening & "Vanced+ microG can't be started :(" toast showing :**
- Install or reinstall Vanced+ MicroG 
- Turn off battery optimization for Vanced+ MicroG
- Allow Vanced+ MicroG run on background or auto start (on heavy customized OS : MIUI,OneUI,FlymeOS,HarmonyOS,etc)
- For Tecno user : Find and open Phone Master app, go to auto start manager, allow Vanced+ microG and YouTube Vanced+ auto start.
- Wipe app data and cache
- Reinstall YouTube Vanced+ client

**There was a problem parsing the package:**
- Check your Android version, Make sure your current Android version meet minimum required Android version.
- Redownload APK file.

-------------------------

## Building

~~**Building from Vanced+ source code**~~

~~**CAUTION : Only Android & Linux are supported! If you are building on unsupported platform, we will refuse to support!**~~

~~Clone essential repository~~

`git clone https://gitlab.com/cuynu/vancedx-patches.git` 

`git clone https://gitlab.com/cuynu/vancedx-integrations.git`

`git clone https://gitlab.com/cuynu/vancedx-cli.git`

~~Open `vancedx-patches` repository in IntelliJ IDEA, make your changes and compile it, after finished compiled, the compiled file should be `vancedx-patches-vX.XXX.jar`~~

~~Open `vancedx-integrations` repository in Android Studio, make your change and compile it, after compiled, the compiled file should be `vancedx-integrations-vX.XXX.apk`~~

~~Open `vancedx-cli` repository in IntelliJ IDEA, make your change and compile it, after compiled, the compiled file should be `vancedx-cli-vX.XXX.jar`~~

~~**Patching YouTube app**~~

~~- For Android users or who lazy to bulit patches & integrations & cli from source, use pre-bulit package here :~~ 

~~[vancedx-patches pre-bulit](https://gitlab.com/cuynu/vancedx-patches/-/releases)~~

~~[vancedx-integrations pre-bulit](https://gitlab.com/cuynu/vancedx-integrations/-/releases)~~


~~[vancedx-cli pre-bulit](https://gitlab.com/cuynu/vancedx-cli/-/releases)~~

~~**Linux :**`~~
~~- Make sure you have installed `openjdk-17`~~
~~- Compile all of essential components or download pre-bulit package above~~
~~- Download YouTube or YouTube Music apk (not apks,apkm) and rename it to youtube.apk (YouTube), ytm.apk (for YouTube Music)~~
- ~~Use Command below to patch.~~

~~**Android :**~~
- ~~Install [Termux](https://termux.dev/en/), open and install openjdk `pkg install openjdk-17` `y` ~~
- ~~type `curl -sLo vancedx-patches.jar [paste download url]`~~
- ~~type `curl -sLo vancedx-integrations.apk [paste download url]`~~
- ~~type `curl -sLo vancedx-cli.jar [paste download url]`~~
- ~~Download YouTube or YouTube Music apk (not apks,apkm) and rename it to youtube.apk (YouTube), ytm.apk (for YouTube Music)~~
- ~~Use Command below to patch.~~


 ~~**Command & example**~~

~~**YouTube (Linux) (dont run as sudo !) :**~~

~~`java -jar 'vancedx-cli-vX.XXX.jar' -p 'vancedx-patches-vX.XXX.jar' -i 'vancedx-integrations-vX.XXX.apk' -lp 'patch-name' --jks 'yourjkskey.jks' --input 'youtube.apk' --output '/VancedXAPKs/base-vx.apk'`~~

**YouTube Music (Linux) (dont run as sudo !) :**

~~`java -jar 'vancedx-cli-vX.XXX.jar' -p 'vancedx-patches-vX.XXX.jar' -i 'vancedx-integrations-vX.XXX.apk' -lp 'patch-name-music' --jks 'yourjkskey.jks' --input 'ytm.apk' --output '/VancedXAPKs/base-vx.apk'`~~

~~**YouTube (Termux):**~~

~~`java -jar 'vancedx-cli.jar' -p 'vancedx-patches.jar' -i 'vancedx-integrations.apk' -lp 'patch-name' --jks 'yourjkskey.jks' --input '/sdcard/Download/youtube.apk' --output '/VancedXAPKs/base-vx.apk'`~~

~~**YouTube Music (Termux):**~~

~~`java -jar 'vancedx-cli.jar' -p 'vancedx-patches.jar' -i 'vancedx-integrations.apk' -lp 'patch-name-music' --jks 'yourjkskey.jks' --input '/sdcard/Download/ytm.apk' --output '/VancedXAPKs/base-vx.apk'`~~

~~Tips : If you getting `Error: Invalid or corrupt jarfile`, redownload essential components then try again.~~

~~After patching process, its will generate base-vx.apk in `/sdcard/VancedXAPKs` (Android) or `/home/username/VancedXAPKs` (Linux)~~

~~For non-root users, install Vanced+ microG and patched `base-vx.apk` then enjoy !~~

~~For root users, follow additional steps on **[Vanced+ Module Template](https://gitlab.com/cuynu/vancedx-module-template)** !~~


## Why this project still exists even ReVanced was a replacement of YouTube Vanced ?
- This project was renamed to "YouTube Vanced+", basically i just add + after Vanced, but its still is a different project than original Vanced or ReVanced. ReVanced are too different from original Vanced and has too many useless feature that enabled by default, specially ReVanced Extended (eg : Hide suggested actions, Hide Subscription tab, Hide every YouTube components that not ADS make original YouTube experience impacted), our goal is continuing Vanced as Vanced+ branding without breaking original YouTube experience, all of features that NOT related to ADS, Downloader or Playback/PIP will be disabled by default
- That means when you install and open YouTube Vanced+ first time, all you see is a YouTube app with no ADS but without any layout modifications, unlike how ReVanced does. you still can modify layout on Vanced+ settings -> Layout but we will never set these tweaks as ON by default.
- Also we still provide pre-bulit YouTube Vanced+ app for who can't patch for yourself just or lazy. Unlike ReVanced (official channel), they never provide pre-bulit app and requires you to bulit from source
- ReVanced Extended are discontinued again recently, so its time for us!

Contributors :

- Cuynu : maintainer
- [Syuugo](https://github.com/s1204IT) : help with japanese translation for Vanced+ microG

## Credits

**[Team Vanced](https://github.com/TeamVanced)** : Old YouTube Vanced official which is closed source

**[ApkTool](https://ibotpeaches.github.io/Apktool/)** : Reverse Engineering tool

**[JadX](https://github.com/skylot/jadx)** : Dex (Smali) to Java decompiler (not too helpful as this doesnt actually decompile to right original Java/Kotlin code)

**[Android Studio](https://developer.android.com/studio/install)/[IntelliJ IDEA](https://www.jetbrains.com/idea/download/download-thanks.html?code=IIC) : IDE to write and implement YouTube Vanced+**

**[inotia00](https://github.com/inotia00)** : Old YouTube Vanced (RVX) based patches (17.34.36-18.21.34)

**[ReVanced Team](https://github.com/revanced)** : ReVanced Team

-------------------------

## [Go back to top of this page](#youtube-vanced-wip)

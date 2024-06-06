# YouTube Vanced+ [placeholder]
**Another open source YouTube modification that does NOT based on any ReVanced code and implemented from scratch, made by [Cuynu](https://gitlab.com/cuynu) !**

# Does this project based on ReVanced/RVX/ReX ?
- If you see someone saying this project are literally ReVanced, that are completely FAKE because they can't even access the Vanced+ source code or its prebulit package and what they said are just old Unofficial Vanced :)

</p>
 <a href="https://telegram.me/vxupdate" ><img src="https://img.shields.io/badge/YouTube Vanced+ Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=dark"></a>
<p align="left">
  <a href="https://discord.gg/U7z2hsxbyM">
    <img alt="Discord" src="https://img.shields.io/discord/1077997663628296333?color=%2300C853&label=YouTube%20VancedX%20Server&logo=discord&logoColor=%2300C853&style=for-the-badge">
  </a>

## Table of Contents

* [Frequently Asked Questions](#frequently-asked-questions)
* [Support this project](#support-this-project)
* [Why this project are not on GitHub?](#why-this-project-are-not-on-github)
* [Why this project still exists even ReVanced was a replacement of YouTube Vanced ?](#why-this-project-still-exists-even-revanced-was-a-replacement-of-youtube-vanced-)
* [Credits](#credits)
* [Features](#features)
* [Building YouTube Vanced+ from source](https://gitlab.com/cuynu/vancedx/-/wikis/Building)
* [Download YouTube Vanced+ APKs](#download)
* [Troubleshoot](https://gitlab.com/cuynu/vancedx/-/wikis/Troubleshoot)
* [Source code](#source-code)

## Introduction 
This project was created after discontinuation of Vanced official aswell wars between Unofficial Vanced and ReVanced Extended. Its not `YouTube Vanced`. The project are in development and will going release soon as possible!

## Features 
- **YouTube Vanced+ blocks ads from YouTube and uses SponsorBlock to skip in-video sponsor segments**
- **The picture-in-picture mode allows watching videos in a floating window**
- **Background play allows playing video sound in background**
- **Override max resolution**
- **Swipe control for brightness and volume**
- **Google login like the original YouTube app using Vanced+ MicroG**
- **Dislike counter re-added using the Return YouTube Dislike database**
- **Download videos and audios from YouTube using external downloader app (NewPipe,Seal,etc...)**
- **Custom video speed**
- **Kids miniplayer**
- **Restore old YouTube layout (Q2/2019, Q2/2020, Q1/2022 layout available)**
- **Restore old Library Tab**
- **Restore old video layout**
- **Many more...**

## Download  

### You won't be able to download **YouTube Vanced+** as this project are not publicly available yet, the repository and the download section are just "placeholder". 
### Instead, you can try old Unofficial Vanced by clicking "Older version" on download section below, sorry for this inconvenient.

**[Older Version](https://gitlab.com/cuynu/vancedx/-/releases)**

-------------------------

### YouTube Vanced+ non-root variant 

**[Download latest version of Vanced+ MicroG](https://gitlab.com/cuynu/VancedxMicroG/-/releases)**

-------------------------

### YouTube Vanced+ root variant (Magisk/KernelSU) 

Notice : Install **[detach module](https://github.com/j-hc/zygisk-detach/releases)** to prevent Play Store from update and replace installed Vanced+.


-------------------------

### YouTube Music Vanced+ non-root variant

**[Download latest version of Vanced+ MicroG](https://gitlab.com/cuynu/VancedxMicroG/-/releases)**

-------------------------

### YouTube Music Vanced+ root variant

Notice : Install **[detach module](https://github.com/j-hc/zygisk-detach/releases)** to prevent Play Store from update and replace installed Music Vanced+ app.

-------------------------

## Source code

**Official YouTube, YT Music and YT Studio app itself are proprietary and closed source, we can't access or have that source code because its are private which only Google/YouTube developer can see its source code. We can only patch and modify YouTube from published compiled apk which is obfuscated by default with ProGuard when they compiling YouTube app.**
- Here is source code for what was modified and all of Vanced+ features, again, DONT ask for YouTube app source code! :

#### [View source code of YouTube Vanced+ (patches)](https://gitlab.com/cuynu/vancedx-patches)

#### [View source code of YouTube Vanced+ (integrations)](https://gitlab.com/cuynu/vancedx-integrations)

#### [View source code of YouTube Vanced+ (cli)](https://gitlab.com/cuynu/vancedx-cli)

-------------------------

## Frequently Asked Questions

FAQ for Vanced+ project :

Q: Why Vanced+ take longer time to be available to anyone?

A: Because my skills. My life always been going with lazy habits, makes me unable to study needed programming language (Kotlin/Java) which is required to reverse engineering YouTube app and create an modifications called Vanced+. Well, this always been my dreams and i want to make its available ASAP. (When Vanced+ available to anyone, this answer will also disappear.)

Q: Does this project implemented from scratch by peoples?

A: No. This project are implemented by only me from scratch but its may contain commits from other contributor after then but it limited to bugfix, translations only.

Q: Does this project contributed by any old Vanced Team members?

A: No, Vanced contributor are not allowed to contribute to Vanced+ project. also, Vanced+ code are all different from Vanced but keep its inspiration

Q: Is there any pre-bulit Vanced+ package so i can just download the package and install without building?

A: Yes, its available on GitLab repository and SourceForge but we can't guarantee that we still can provide pre-bulit package for long time as Vanced has been taken down from 2022 due to distributing modified YouTube APKs (they also selling NFTs).

Q: Does Vanced+ support Android 5 & 6 & 7 ?

A: Nope, because YouTube already dropped support new version for these Android version and we do not support older version as it will return with 400 error soon

Q: Why Q2 2019 layout greyed out and can't be selected on layout selection in Vanced+ settings -> Layout settings -> Override app layout ?

A: From 2020 and above, YouTube bulit-in layout changed much component, make it incompatible when override Q2 2019 layout so in order to use Q2 2019 layout, it requires specific build of Vanced+ named q2y19, you have to download the build or patch with q2y19-layout (remember that you can't patch both q2y19-layout and newer layout to the same app)

Q: Does override older layout also spoof app version to older version ?

A: Nope, this method directly override layout to older layout depend on your selection but does not spoof app version to older version as Q2/2019, Q2/2020, Q1/2022 layout are all from older version which is deprecated long time ago, spoofing to older version will lead to 400 error response.

## Contributing to this project

Thanks for your support, but you can only contribute to this project in two ways :
- Contribute translations for Vanced+
- Report issues with full details info (logcat)
Why not bugfixes, new features?
- This limitations is to prevent someone put or use ReVanced related code to contribute to this project, as my aim is Vanced+ should be NOT contains any ReVanced related code.


Contributors :

- Cuynu : maintainer
- [Syuugo](https://github.com/s1204IT) : help with japanese translation for Vanced+ microG


## Why this project still exists even ReVanced was a replacement of YouTube Vanced ?
- This project was renamed to "YouTube Vanced+", basically i just add + after Vanced, but its still is a different project than original Vanced or ReVanced. ReVanced are too different from original Vanced and has too many useless feature that enabled by default, specially ReVanced Extended (eg : Hide suggested actions, Hide Subscription tab, Hide every YouTube components that not ADS make original YouTube experience impacted), our goal is continuing Vanced as Vanced+ branding without breaking original YouTube experience, all of features that NOT related to ADS, Downloader or Playback/PIP will be disabled by default
- That means when you install and open YouTube Vanced+ first time, all you see is a YouTube app with no ADS but without any layout modifications, unlike how ReVanced does. you still can modify layout on Vanced+ settings -> Layout but we will never set these tweaks as ON by default.
- Also we still provide pre-bulit YouTube Vanced+ app for who can't patch for yourself just or lazy. Unlike ReVanced (official channel), they never provide pre-bulit app and requires you to bulit from source

## Why this project are NOT on GitHub?
- This project are available on GitHub "in the past" with >3k stars and >3.5M total downloads. But in 2024/01 GitHub requires all old users MUST be enable 2FA Authentication with DOTP, i don't want to do that as i usually factory reset and install/testing custom ROMs on my device (I have own YT Channel : [@cuynu](https://youtube.com/@cuynu/videos)) which is for that purpose but that not big issues, the big issues here is i was too lazy to backup secret code (used to generate 2FA code), so i deleted almost all repository on GitHub include my personal and VancedxMicroG project. 

After a month, i recreated ytvanced repository on github but its only a wrapper to redirect user to this GitLab repository. I stopped using GitHub since 2024/05. 

## Support this project
- Vanced+ are NON-PROFIT project and i don't want to earn any moneys from it, even if you want.
- Instead, you can support me by subscribing my [personal YouTube channel](https://youtube.com/@cuynu/community) but remember its content are just custom ROMs, rooting Android devices and some other guides but you can just ignore all of them. Also, you can request Vanced+ updates/report issues if you don't want to use GitLab by commenting on any videos i uploaded to. That enough to makes me happy and continue with Vanced+ development:)

## Credits

**[Team Vanced](https://github.com/TeamVanced)** : Old YouTube Vanced official which is closed source, I use its icon assets (Vanced, SponsorBlock, RYD icons)

**[inotia00](https://github.com/inotia00)** : Old YouTube Vanced (RVX) based patches which is used on Unofficial Vanced v17.34.36-v18.21.34 (this is my bad part)

**[ReVanced Team](https://github.com/revanced)** : ReVanced Team for CLI used to build old Unofficial Vanced

-------------------------

## [Go back to top of this page](#youtube-vanced-placeholder)


# Magisk Configuration

## Aims

A minimal set of instructions to configure and setup Magisk to pass Play Integrity, and hide root from apps.

## Overview
> For simplicty going forwards the guide, in this very limited brief overview of Magisk, will only refer to Official Magisk and the known methods to pass Integrity Check/SafetyNet and for root hiding methods. This is not to disparage the other variants of Magisk, Alpha and Delta, as they have been appreciated and served their purpose, particularly in the gap period where MagiskHide (the original root hiding method) was removed, and an alternate was found. As there are often rapid changes in Alpha/Delta forks, a decision was made for simplicty's sake, in this brief Magisk guide to concentrate on Official. Users can of course chose to use an unofficial Magisk fork, but we wont discuss them here.

This guide wont cover the installation of Magisk as it can vary by device, and those installation steps are best handled in the existing XDA threads for Magisk, or on occasion in your devices specific XDA threads on how to root x device. 

**Please Note:** Please do NOT post Magisk issues here, they will be closed without reply.

## Requirement(s)
- Magisk Official
- Shamiko
- Universal SafetyNet Fix

## Download Links

Magisk:
- [Magisk Official:](https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877/)

Modules:
- [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases)
- [Universal SafetyNet Fix (USNF)](https://github.com/kdrag0n/safetynet-fix/releases) - Official.
- \* [Universal SafetyNet Fix (USNF)](https://github.com/Displax/safetynet-fix/releases) - Modified by **Displax**.

\* **Please Note: At time of writing (06/02/2023 DD/MM/YYYY)** Kdrag0n's official USNF 2.4.0 does have some issues, if you experience any, please use Displax's 2.3.1 Mod 2.1 (or better) instead.

## Method To Achieve Aims

1) Pass Integrity Check
  - If you think you have a correctly configured Magisk (using Magisk and the modules listed above), try to [Check Integrity](Integrity-Check.md) now
  - Otherwise install Magisk, and then the modules above before rebooting and continuing on to [Check Integrity](Integrity-Check.md)

2) Hide Root From Apps
  - If you think you have Magisk configured correctly to hide root from apps [return home](README.md)
  - Othwerise continue [here](Magisk-Hide.md) to configure your Magisk installation to hide root from apps


## Pages (How To)
- [Integrity Check](Integrity-Check.md)
- [Hide Root](Magisk-Hide.md)


[<i>Return Home</i>](README.md)

<!--List of page links-->
[HMA Home]: (README.md)
[Install LSPosed]: Install-LSPosed.md
[Install HMA]: Install.md
[Compare HMA Blacklist vs Whitelist Modes]: BlacklistvsWhitelist.md
[Configure BlackList]: BlackList.md
[Configure WhiteList]: WhiteList.md
[Test HMA]: TestHMA.md
[Backup and Restore]: BackupAndRestore.md
[KnownIssues]: https://github.com/mModule/guide_hma/blob/master/KnownIssues.md

[Magisk Pages]: MagiskTOC.md
[Magisk USNF]: https://github.com/mModule/guide_hma/blob/master/Magisk-SafetyNet-Fix.md
[PlayIntegrity]: https://github.com/mModule/guide_hma/blob/master/Integrity-Check.md
[MagiskHide]: https://github.com/mModule/guide_hma/blob/master/Magisk-Hide.md

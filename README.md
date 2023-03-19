# Hide My Applist Guide
This is just a quick guide to hopefully make it a little easier for people new to Hide My Applist (often referred to as **HMA** from hereon in



### Description

In the simplest terms it aims to stop one app detecting a list of other installed apps. Most notably it can often help stop your banking app(s) from
 detecting if you have any of the apps it considers harmful (ie. is on their apps internal blacklist) - Eg. the magisk App, or Teamviewer (a bank flagged this as riskware on my device.)...

In Android 13 Google has added extra protections to prevent Applist detection abuse by apps but its early days and apps have various ways to bypass Android/Google protections...

---

### Requirement(s)

- A ROM with a working Magisk root installation (see links to threads for official Magisk and Magisk Delta below).

Ideally you should be passing deviceIntegrity Play Integrity API check (successor to SafetyNet). Currently for most people this requires:
- **Universal SafetyNet Fix Official** from **kdrag0n** from https://github.com/kdrag0n/safetynet-fix  or alternately **2.3.1 Mod 2.1** (or better) from **Displax** https://github.com/Displax/safetynet-fix/releases (depending on which version is later and more effective on your device - if in doubt, try the kdrag0n offical first). 

   **Please Note: At time of writing (06/02/2023 DD/MM/YYYY)** Kdrag0n's offical USNF 2.4.0 does have some issues, if you experience any, please use Displax's 2.3.1 Mod 2.1 (or better) instead.

Additionally, native Magisk denylist should be swapped for proper root hiding:

- If running **Magisk official**, **Shamiko** with **Enforce Deny List** toggled **OFF** from https://github.com/LSPosed/LSPosed.github.io/releases
- If running **Magisk Delta**, check with https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/ for best hiding method

Further hiding of compromised runtime environment indicators include:

- A renamed/obfuscated Magisk App (I rename mine 'App', because im lazy and it puts it at the top of the App list when I'm adding it to HMA both during setup and after restoring HMA config after a new ROM flash/factory reset, and HMA installation.)

   **Please Note:**  Methods used to pass Integrity Check, and for extra 'root-trace' hiding, and therefore referenced modules like Shamiko, may change at any time, so please visit and watch the following XDA threads:
   - **Universal SafetyNet Fix:** https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-3-1.4217823/
   - **Magisk - The Age Of Zygisk:** https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877/
   - **Magisk Delta:** https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/

- **Lsposed for systemless XPosed framework:** https://github.com/LSPosed/LSPosed/releases
   Either Zygisk or Riru version depending on your fork of Magisk

   For most people on the official Magisk builds, this will be the Zygisk build

   For people on the Magisk Delta build by **huskydg** my current understanding is:
   - if you have **enabled Zygisk** in your Magisk Manager, you should install the Zygisk build
   - if you have **disabled Zygisk** in your Magisk Manager, you should install the Riru build


- **Hide My Applist (a v3 branch apk):** https://github.com/Dr-TSNG/Hide-My-Applist/releases

    **Note #1 (Versions):** Its now **SAFE** to use the downloader in **Lsposed Manager** to download it (when this guide was originally posted LSPosed was only serving v2.x builds as v3.x were still in beta)   
    
    **Note #2 (Bootloops):** HMA v2.x also used a companion magisk module that you MUST now uninstall if upgrading... It's use with 3.x will cause bootloops.  HMA v3.x **DOES NOT** require a magisk module to achieve its purpose!

---

### How to
- [Install and configure HMA](Install.md)
- [Create a blacklist template](BlackList.md)
- [Create a whitelist template](WhiteList.md)

---

### Reporting Issues Or Providing Feedback On The Guide

Please report any issues you may find with the guide above via the [Issues](https://github.com/adrianmmiller/Hide-My-Applist-Guide/issues) tab

# Hide My Applist Guide
This just a quick guide to hopefully make it a little easier for people new to Hide My Applist (often referred to as **HMA** from hereon in



### Description

In the simplest terms it aims to stop one app detecting a list of other installed apps, most notably it can often help stop your say banking app
 detecting if you have any of the apps it considers harmful on their apps on internal blacklist - like the magisk app, or like one of found 
the other day, the banking app wouldnt run with Teamviewer installed as it flagged this as riskware. Android 13 was flagged to have this 
functionality inbuilt, but its early days yet to see whether this is indeed in effect and effectual

---

### Requirement(s)

- A ROM with a working Magisk root installation (see links to threads for official Magisk and Magisk Delta below), this means ideally you should have a passing Integrity check (successor to SafetyNet) - currently for most people this requires:
- **Universal SafetyNet Fix Official** from **kdrag0n** from https://github.com/kdrag0n/safetynet-fix  or alternately **2.3.1 Mod 2.1** (or better) from **Displax** https://github.com/Displax/safetynet-fix/releases (depending on which version is later and more effective on your device - if in doubt, try the kdrag0n offical first). 

   **Please Note: At time of writing (6/2/22023 DD/MM/YYYY)** Kdrag0n's offical USNF 2.4.0 does have some issues, if you experience any, please use Displax's 2.3.1 Mod 2.1 (or better) instead.

- If running **Magisk official**, **Shamiko** with **Enforce Deny List** toggled **OFF** from https://github.com/LSPosed/LSPosed.github.io/releases
- If running **Magisk Delta**, check with https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/ for best hiding method
- A renamed Magisk Manager app - i rename mine App, because im lazy and it puts it at the top of the App list when im adding it to HMA both during setup, and after restoring HMA config after a new ROM flash/factory reset, and HMA install

   **Please Note:**  The method used to pass Integrity Check, and for Magisk hiding methods, and therefore referenced modules like Shamiko, may change at any time, so please visit and Watch the following XDA threads
   - **Universal SafetyNet Fix:** https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-3-1.4217823/
   - **Magisk - The Age Of Zygisk:** https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877/
   - **Magisk Delta:** https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/

- **Lsposed:** https://github.com/LSPosed/LSPosed/releases

   Either Zygisk or Riru version depending on your fork of Magisk

   For most people on the official Magisk builds, this will be the Zygisk build

   For people on the Magisk Delta build by **huskydg** my current understanding is:

   - if you have **enabled Zygisk** in your Magisk Manager, you should install the Zygisk build
   - if you have **disabled Zygisk** in your Magisk Manager, you should install the Riru build


- **Hide My Applist (a v3 branch apk):** https://github.com/Dr-TSNG/Hide-My-Applist/releases

    **Note #1 (Versions):** Its now **SAFE** to use the downloader in **Lsposed Manager** to download it (at original time of putting up this guide it was only serving the older v2 builds)   
    
    **Note #2 (Bootloops):** HMA v2 also used a companion magisk module, that if you forgot uninstall when uninstalling HMA itself, would cause a bootloop.  HMA v3 **DOES NOT** require a magisk module to achieve its purpose, so please **DO NOT** attempt to install **HMA v3** over the top of **HMA v2**, or install the magisk module from **HMA v2** separately, in conjunction with **HMA v3**. If you have **HMA v2** installed, please uninstall the **HMA v2** magisk module via Magisk Manager, then remove HMA, and reboot, before installing **HMA v3**

---

### How to
- [Install and configure HMA](Install.md)
- [Create a blacklist template](BlackList.md)
- [Create a whitelist template](WhiteList.md)

---

### Reporting Issues Or Providing Feedback On The Guide

Please report any issues you may find with the guide above via the [Issues](https://github.com/adrianmmiller/Hide-My-Applist-Guide/issues) tab

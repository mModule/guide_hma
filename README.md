# Hide My Applist Guide

This is just a quick guide to hopefully make it a little easier for people new to Hide My Applist (often referred to as **HMA** from hereon in)

## <ins>Description</ins>

In the simplest terms it aims to stop one app detecting a list of other installed apps. Most notably it can often help stop your banking app(s) from detecting if you have any of the apps it considers harmful (ie. is on their apps internal blacklist) - Eg. the magisk App, or Teamviewer (a bank flagged this as riskware on my device.)

In Android 13 Google has added extra protections to prevent Applist detection abuse by apps but its early days and apps have various ways to bypass Android/Google protections...

## <ins>Requirement(s)</ins>

- A Magisk Installation That Passes Integrity Check API 
  If you think you have a correctly installed and configured Magisk setup that passes Integity Check, then you may like to skip ahead to [here](Integrity-Check.md)
  
  Otherwise please continue [here](Magisk-SafetyNet-Fix.md)
- A Magisk Installation That Hides Root From Apps see [here](Magisk-Hide.md)
  If you think you have a corretcly installed an dconfigured Magisk setup, then you may like to check [here](Integrity-Check.md)

- **Lsposed for systemless XPosed framework:** from [here](https://github.com/LSPosed/LSPosed/releases)

  Either Zygisk or Riru version depending on your fork of Magisk

  For most people on the official Magisk builds, this will be the Zygisk build

  For people on the Magisk Delta build by **huskydg** my current understanding is:

  - if you have **enabled Zygisk** in your Magisk Manager, you should install the **Zygisk** build
  - if you have **disabled Zygisk** in your Magisk Manager, you should install the **Riru** build

- **Hide My Applist (a v3 branch apk):** from [here](https://github.com/Dr-TSNG/Hide-My-Applist/releases)

  **Note #1 (Versions):** Its now **SAFE** to use the downloader in **Lsposed Manager** to download/update it (when this guide was originally posted LSPosed was only serving v2.x builds as v3.x were still in beta)   

  **Note #2 (Bootloops):** HMA v2.x also used a companion magisk module that you MUST now uninstall if upgrading... It's use with 3.x will cause bootloops.  HMA v3.x **DOES NOT** require a magisk module to achieve its purpose!



## <ins>How to</ins>

- [Install and configure HMA](Install.md)
- [Create a blacklist template](BlackList.md)
- [Create a whitelist template](WhiteList.md)

### Reporting Issues Or Providing Feedback On The Guide

Please report any issues you may find with the guide above via the [Issues](https://github.com/mModule/guide_hma/issues) tab

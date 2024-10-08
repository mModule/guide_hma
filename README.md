# Hide My Applist Guide

---

## Description

In the simplest terms it aims to stop one app detecting a list of other installed apps.<br>
Most notably it can often help stop your banking app(s) from detecting if you have any of the apps it considers harmful. (ie. is on their apps internal blacklist).<br>
<i>Example: the Magisk App, or Teamviewer (a bank flagged this as riskware on my device).</i>

In Android 13, Google has added extra protections to prevent Applist detection abuse by apps.<br>
<i>Its still early days for Android 13 and apps have various ways to bypass Android/Google protections.</i>

Besides hiding root from sensitive (secure) apps, you can also hide installed apps from an app store.<br>
<i>This is convenient if you have an app installed that is:<br>
- Installed from a different app store.
- Modified.
- Older version.<br></i>

## Requirement(s)
- Magisk
  - <i>Preferably a Magisk installation (setup) that passes Play Integrity.</i>
- LSPosed
  - <i>Systemless Xposed framework.</i>

## Download Links
- [LSPosed framework](https://github.com/LSPosed/LSPosed/releases)
- [Hide My Applist (HMA)](https://github.com/Dr-TSNG/Hide-My-Applist/releases)
  
Or, alternately a new fork of HMA, by **PumPCin**
- [Hide My App List (HMAL)](https://github.com/pumPCin/HMAL/releases)  

## Pages (How to)
- [Install LSPosed](Install-LSPosed.md)
- [Install HMA](Install-HMA.md)
- [Compare HMA Blacklist vs Whitelist Modes](BlacklistvsWhitelist.md)
- [Configure HMA using the Blacklist Mode](BlackList.md)
- [Configure HMA using the Whitelist Mode](WhiteList.md)
- [Hiding an app from Store](PlayStore.md)
- [Testing HMA](TestHMA.md)
- [Backup and Restore HMA settings](BackupAndRestore.md)

## Notes
<b>Note: Please consider any mention of HMA to also interchangeably refer to HMAL (Hide My App List, PumPCins fork)</b>

<b>This guide is for Hide My Applist v3.x</b>
>1. It is now <b>safe</b> to use the downloader in <i>LSPosed Manager</i> to download/update HMA.<br>
<i>(When this guide was originally posted LSPosed was only serving v2.x builds as v3.x were still in beta)</i><br>

>2. HMA v2.x required a companion magisk module that <b>must be uninstall</b> when updating to HMA v3.x.<br>
<b><i>It's use with v3.x will cause bootloops.</i></b><br>
<i>HMA v3.x <b>does not</b> require a magisk module to achieve its purpose!</i><br>

<b>LSPosed for systemless XPosed framework</b>
>Either Zygisk or Riru version depending on your fork of Magisk.<br>
For most people on the official Magisk builds, this will be the Zygisk build.

<b>Magisk</b>
>Configuration of Magisk is outside the scope of this guide.<br>
<i>A minimal set of instructions has been written for completeness.<br>
See [Magisk Configuration](Magisk.md) for Magisk setup and passing Play Integrity.</i><br>

<!--
<b>Testing/Guide Creation Environment</b>
>This guide was first conceived, written and tested on Android 12, then updated to Android 13.<br>
Using the current version of apps and modules at the time of testing.<br>

><i>Certain steps may not reflect your experience on earlier versions of Android, apps or modules.<br>
If you find a difference in your experience, please let us know via the [Issues](https://github.com/mModule/guide_hma/issues) tab, so we can address it, thanks.</i><br>

## Known Issue(s)
- [HMA is still detected by x app](KnownIssues.md#hma-is-still-detected-by-x-detection-app)
- Android 14 (Beta).<br>
  - HMA (v3.1.1), according to reports, will result in an instant reboot on Android 14 beta .<br>
-->

---

## Providing Feedback On The Guide
Please report any issue(s) with the guide or enhancement via the [Issues](https://github.com/mModule/guide_hma/issues) tab.<br>
<i>Please do not report an issue with Android or HMA "Beta" version(s) to this guide.</i>

---

## Credits

- 72sydney (adrianmmiller) for guide creation, content contributions and typos.
- ipdev for content contributions, layout and formatting.
- pndwal for content contributions.
- zgfg for content contributions and for getting me into this HMA thing.
- John Wu and team for all things [Magisk](https://github.com/topjohnwu/Magisk).
- Dr-TSNG (nullptr) for [HMA](https://github.com/Dr-TSNG/Hide-My-Applist).
- LoveSy and team for [LSPosed](https://github.com/LSPosed/LSPosed).

# Using Whitelist mode

You should be on the HMA Home tab at this point, if not, please open HMA from your app drawer

Unlike the blacklist method, in this whitelist method doesnt require creating a template, just configuring apps

## Configuring Apps

On the Home tab, tap **App Manage**

![](image/wl01.jpg?raw=true)

On the following screen, you'll see a list of all your apps, select any which you want to make visible to other apps, by tapping them, one at a time

![](image/wl02.jpg?raw=true)

  This will normally be:
  - **Google Pay/Wallet**
  - **Banking apps**
  - Any "detection" apps (apart from Momo)(see list in [Testing HMA](TestHMA.md) page for common detection apps)
  
  For each app you add, do the following:
  - Tap the toggle to the right of **Enable Hide** to enable hiding
  - Tap the toggle to the right of **Work Mode** to enable Whitelist
  - Tap the toggle to the right of **Exclude System Apps**
  - Tap the back navigation key, swipe back (if using gesture navigation) or tap the back arrow in top left to return to app list, and repeat the above few steps for each app you wish to add

  ![](image/wl03.jpg?raw=true)

## **Finalizing And 1st Boot**   

- Close out from HMA
- Reboot your device to activate HMA and the configuration you just setup
- After reboot has completed, launch HMA from your app drawer

   ![](image/HMA12.jpg?raw=true)

  You should show the following screen, showing the status as Activated
  
   ![](image/HMA13.jpg?raw=true)

  **Please Note:** 
  - Any time you make a configuration change in HMA, you need to reboot for it to take effect
  - It can take several minutes on first boot after being configured, for HMA to take effect. Ive noticed this on several ROM flashes. I would wait a good 5 minutes before testing, or opening any apps you have added via HMA after this first initial boot.

---
Continue to :<br>
[<b>Testing HMA</b>](TestHMA.md)<br>

Jump to :<br>

[Install LSPosed] - [Install HMA] - [Configure BlackList Mode] - [Configure WhiteList Mode] - [Backup and Restore]<br>

[<i>Return Home</i>](README.md)

<!--List of page links-->

[HMA Home]: README.md
[Install LSPosed]: Install-LSPosed.md
[Install HMA]: Install.md
[Compare HMA Blacklist vs Whitelist Modes]: BlacklistvsWhitelist.md
[Configure BlackList Mode]: BlackList.md
[Configure WhiteList Mode]: WhiteList.md
[Test HMA]: TestHMA.md
[Backup and Restore]: BackupAndRestore.md
[Known Issues]: KnownIssues.md

[Magisk Pages]: MagiskTOC.md
[Magisk USNF]: Magisk-SafetyNet-Fix.md
[PlayIntegrity]: Integrity-Check.md
[MagiskHide]: Magisk-Hide.md



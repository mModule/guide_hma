# Using Whitelist mode

You should be on the HMA Home tab at this point, if not, please open HMA from your app drawer.

Unlike the blacklist method, this whitelist method doesnt require creating a template, just configuring apps.

## Configuring Apps

On the Home tab, tap <b>App Manage</b>

![](image/wl01.jpg?raw=true)

On the following screen, you'll see a list of all your apps, select any form which you want to hide other apps by tapping them, one at a time.

![](image/wl02.jpg?raw=true)

This will normally be:
  - <b>Banking apps</b>
  - Any "detection" apps that look for applist (Momo doesn't)(see list in [Testing HMA](TestHMA.md) page for common detection apps)
i.e. Any apps which complain about root or are sensitive to other apps for their own reasons (eg. the app might compromise security / code execution environment) are a candidate for adding here.
  
  For each app you add, do the following:
  - Tap the toggle to the right of <b>Enable Hide</b> to enable hiding
  - Tap the toggle to the right of <b>Work Mode</b> to enable Whitelist
  - Tap the toggle to the right of <b>Exclude System Apps</b> to exclude as recommended
  - Tap the back navigation key, swipe back (if using gesture navigation) or tap the back arrow in top left to return to app list, and repeat the above few steps for each app you wish to add

  ![](image/wl03.jpg?raw=true)

## **Finalizing and 1st Boot**

- Close out from HMA
- Reboot your device to activate HMA and the configuration you just setup
- After reboot has completed, launch HMA from your app drawer

   ![](image/HMA12.jpg?raw=true)

  You should show the following screen, showing the status as Activated
  
   ![](image/HMA13.jpg?raw=true)

  <b>Please Note:</b>
  - Any time you make a configuration change in HMA, you need to reboot for it to take effect
  - It can take several minutes on first boot after being configured, for HMA to take effect. Ive noticed this on several ROM flashes. I would wait a good 5 minutes before testing, or opening any apps you have added via HMA after this first initial boot.

---
Continue to :<br>
[<b>Hiding from Store</b>](PlayStore.md)

Jump to :<br>
[Install LSPosed] - [Install HMA] - [Compare HMA Blacklist vs Whitelist Modes] - [Configure Blacklist Mode] - [Testing HMA] - [Backup and Restore]<br>

[<i>Return Home</i>](README.md)

<!--List of page links-->
[HMA Home]: README.md
[Install LSPosed]: Install-LSPosed.md
[Install HMA]: Install-HMA.md
[Compare HMA Blacklist vs Whitelist Modes]: BlacklistvsWhitelist.md
[Configure Blacklist Mode]: BlackList.md
[Configure Whitelist Mode]: WhiteList.md
[Hide from Store]: PlayStore.md
[Testing HMA]: TestHMA.md
[Backup and Restore]: BackupAndRestore.md
[KnownIssues]: KnownIssues.md

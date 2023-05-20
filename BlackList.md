# Using Blacklist mode

You should be on the HMA Home tab at this point, if not, please open HMA from your app drawer.

## Template Creation

Tap on **Template Manage**

![](image/HMA04.jpg?raw=true)

On the next screen tap **Create A Blacklist Template**

![](image/HMA05.jpg?raw=true)

On the following screen, type **root** into the **Template Name** box, then tap **Edit List**, just below and to the right.

![](image/HMA06.jpg?raw=true)

Selecting root, HMA and lsposed apps...

On the following screen, you'll see a list of all your apps, select the following, by tapping to tick them:

- **Magisks renamed (hidden) app** - mine's always App (because as i said, im lazy and its easy to add)*
- Any other root apps or apps simply related to root or custom modification etc. (that banks may flag as security risks, indicators of custom mods or compromised runtime environment). Environment checking apps like Momo are an example. 
- **HMA** - obviously
- Any other Xsposed/LSposed apps

*Nb. Anytime you take Restore the Magisk app option and then Hide the Magisk app again you'll need to re-add it as, while the old randomised package name is retained in HMA, you will now be using a new one...

When youre done, tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen.

![](image/HMA07.jpg?raw=true)

## Configuring Apps

From the main HMA Settings menu, tap **App Manage**

![](image/HMA08.jpg?raw=true)

On the following screen, you'll see a list of all your apps, select any which you want to hide root/mod related apps, HMA and other xposed/lsposed modules from by tapping to tick them.

  This will normally be:
  
  - **Banking apps**
  - Any "detection" apps (see list in [Testing HMA](TestHMA.md) page for common detection apps)

  i.e. Any apps which complain about root or are sensitive to other apps for their own reasons (eg. the app might compromise security / code execution environment) are a candidate for adding here.

  For each app you add, do the following:
   
  - Tap the toggle to the right of **Enable Hide** to enable hiding
  - Under **Template Config** (toward bottom) tap **Using 0 Template**

  ![](image/HMA09.jpg?raw=true)

  On the popup window that appears:

  - Tap the checkbox next to **root** to select the root blacklist template
  - Tap **OK** to close the popup window
   
  ![](image/HMA10.jpg?raw=true)

  You should now see a screen similar to this for the app you just configured

  ![](image/HMA11.jpg?raw=true)

  When youre done, tap back navigation key, swipe back or tap the back arrow in top left to return to app list, and repeat the above few steps for each app you wish to hide root-related apps, HMA and other xposed/lsposed modules from.

  Now tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
   
## Finalizing And 1st Boot

- Close out from HMA
- Reboot your device to activate HMA and the configuration you just setup
- After reboot has completed, launch HMA from your app drawer

  ![](image/HMA12.jpg?raw=true)

  You should show the following screen, showing the status as Activated

  ![](image/HMA13.jpg?raw=true)

  **Please Note:** 
  - Any time you make a configuration change in HMA, you need to reboot for it to take effect
  - It can take several minutes on first boot after being configured, for HMA to take effect. Ive noticed this on several ROM flashes. I would wait a good 5 minutes before testing, or opening any apps you have hidden via HMA after this first initial boot.

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
[Compare HMA Blacklist vs Whitelist Methods]: BlacklistvsWhitelist.md
[Configure BlackList Mode]: BlackList.md
[Configure WhiteList Mode]: WhiteList.md
[Test HMA]: TestHMA.md
[Backup and Restore]: BackupAndRestore.md
[Known Issues]: KnownIssues.md

[Magisk Pages]: MagiskTOC.md
[Magisk USNF]: Magisk-SafetyNet-Fix.md
[PlayIntegrity]: Integrity-Check.md
[MagiskHide]: Magisk-Hide.md

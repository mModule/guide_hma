### Create A Blacklist Template

   When the **Settings** screen opens, tap on **Template Manage**

   ![](image/HMA9.jpg?raw=true)

   On the next screen tap **Create A Blacklist Template**

   ![](image/HMA10.jpg?raw=true)

   On the following screen, type **root** into the **Template Name** box, then tap **Edit List**, just below and to the right

   ![](image/HMA11.jpg?raw=true)


   Selecting root, HMA and lsposed apps...

   On the following screen, you'll see a list of all your apps, select the following, by tapping to tick them:

   - **Magisks renamed (hidden) app** - mines always App (because as i said, im lazy and its easy to add)
   - **HMA** - obviously
   - Any Xsposed/LSposed apps


   When youre done, tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen

   ![](image/HMA12.jpg?raw=true)



- **Configure Apps**

   From the main HMA Settings menu, tap **App Manage**

   ![](image/HMA13.jpg?raw=true)

   On the following screen, you'll see a list of all your apps, select any which you want to hide root, HMA and any xposed/lsposed modules from, by tapping to tick them

   This will normally be:
   
   - **Google Pay/Wallet**
   - **Banking apps**
   - Any "detection" apps (see list in **Testing HMA** section below for common detection apps)

      i.e. Any apps which complain about root or other sensitive app detection are a candidate for adding here.

      For each app you add, do the following:
   
      - Tap the toggle to the right of **Enable Hide** to enable hiding
      - Under **Template Config** (toward bottom) tap **Using 0 Template**

         ![](image/HMA14.jpg?raw=true)

      On the popup window that appears:

      - Tap the checkbox next to **root** to select the root blacklist template
      - Tap **OK** to close the popup window
   
         ![](image/HMA15.jpg?raw=true)

   You should now see a screen similar to this for the app you just configured

   ![](image/HMA16.jpg?raw=true)

   When youre done, tap back navigation key, swipe back or tap the back arrow in top left to return to app list, and repeat the above few steps for each app you wish to hide root, HMA and any xposed/lsposed modules from

   When youre done selecting all apps you wish to hide root, HMA and any xposed/lsposed modules from, tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
   
- **Finalizing And 1st Boot**   

   Close out from HMA

   Reboot your device to activate HMA and the configuration you just setup

   After reboot has completed, launch HMA from your launcher

   ![](image/HMA17.jpg?raw=true)

   You should show the following screen, showing the status as Activated

   ![](image/HMA18.jpg?raw=true)


   **Please Note:** 
   - Any time you make a configuration change in HMA, you need to reboot for it to take effect
   - It can take several minutes on first boot after being configured, for HMA to take effect. Ive noticed this on several ROM flashes. I would wait a good 5 minutes before testing, or opening any apps you have hidden via HMA after this first initial boot.

---

### Testing HMA

Of course you're probably going want to test the apps you primarily installed HMA to assist with, but you can of course test with the following test apps (some of which you may have had installed already and added during the **Configure Apps** step.

One, **Applist Detector**, is linked in the main screen of HMA itself, but not installed by default, so on tapping it for the first time, it will prompt you to download it, or you can grab it before hand from https://github.com/Dr-TSNG/ApplistDetector/releases/

The other well known detection tools are:

- **Momo** from https://t.me/magiskalpha (TG only...may need to scroll to find)

- **Ruru** from https://github.com/byxiaorun/Ruru/releases (Github)

- **Oprek Root Detector** from https://play.google.com/store/apps/details?id=com.godevelopers.OprekCek (Google Play Store)

- **TB Checker - SafetyNet & Root** from https://play.google.com/store/apps/details?id=krypton.tbsafetychecker (Google Play Store)

- **Security Check - Device Compliance** from https://play.google.com/store/apps/details?id=com.hce.compliance.checker (Google Play)

**Please Note:**
- After adding apps to the root blacklist or other configuration changes, you need to not only reboot to allow the changes to take effect, but also to force close and clear data for any of the above testing apps before testing again.
- The results of the tests are beyond the scope of this guide, and best discussed in the main Magisk threads, not here, as this is merely a guide for HMA, and as such would be the worst place to have your posts seen due to the low volume of traffic. Also please do not PM me about test results, all such PM's will go directly to /dev/null/

---

### Additional Notes & Known/Suspected Issues:

- **HMA is still dectected by X detection app:**

   You may need to activate Vold App Data Isolation - Be aware a couple of people have reported that toggling this on has ended in tears for them, these people though have non-standard setups, using modules and apps which i and most people dont run and wouldnt recommend, and so therefore their experiences may be due to changes they have made to their systemns outside the scope of this guide. 
   
   The following issues were highlighted, thanks **stillhard**
   - https://github.com/Dr-TSNG/Hide-My-Applist/issues/253
   - https://github.com/Dr-TSNG/Hide-My-Applist/issues/247
   

   Now that youve been warned, should you wish to enable Vold App Data Isolation:
   
   From the HMA home screen: 
   
   ![](image/HMA18b.jpg?raw=true)
   
   - Tap **Settings** (gear icon in bottom right) 
   - Scroll to **Module** section 
   - Tap **Data Isolation**
   
   ![](image/VOLD1.jpg?raw=true)
   
   - Tap to toggle **Vold App Data Isolation** to **ON**
   
   ![](image/VOLD2.jpg?raw=true)
   
   - Tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
   
   - Reboot device 

---

### HMA Backup & Restore

To save recreating the root blacklist template and apps list, you can backup HMA's config and restore it after a clean ROM flash or post factory reset

Backup:

- From the main HMA screen scroll down if need be (due to ad placement) and tap **Backup**
- Locate where you want to save the **HMA_Config.json** (prenamed) file and then tap **Save**
- Copy **HMA_Config.json** off device for safe keeping


Restore:

- Copy **HMA_Config.json** onto device if needed
- Run through the setup as above until you reach the main HMA window at the **Configure HMA** stage
- From the main HMA screen scroll down if need be (due to ad placement) and tap **Restore**
- Locate where you stored the [B]HMA_Config.json[/B] (prenamed) file and then tap **Restore**
- If you rename (hide) the Magisk Manager app, and you should, you will need to add the (new) renamed Magisk Manager's app to the root blacklist template after restoring the HMA config:
   - From the main HMA screen, tap **Manage Template**
   - Tap **root** template
   - Tap **Edit List** (the first one) to the right of **X Apps Invisible**
   - Scroll to find your renamed Magisk Managers app and select it
   - Tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
   - Close out from HMA
   - Reboot your device to activate HMA and the configuration you just restored

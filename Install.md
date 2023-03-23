### Install and configure HMA

- **Install Lsposed**

   From your launcher, open your Magisk App (yours is hopefully renamed as mentioned earlier) and switch to the Modules tab (at bottom), then tap **Install From Storage** at the top of screen.

   ![](image/HMA1.jpg?raw=true)

   On the next screen, select the directory where you stored the Lsposed zip, and then tap it

   ![](image/HMA2.jpg?raw=true)

   The Lsposed module will now install and when complete you should tap **Reboot** to reboot your device

   ![](image/HMA3.jpg?raw=true)

   After your device reboots you will see a prompt to add a shortcut to your launcher; you can manually place it but i usually just tap **Add Automatically** and let it sort it out for me as my main launcher screen is full, This overflows onto a second launcher screen...

  ![](image/HMA4.jpg?raw=true) ![](image/HMA5.jpg?raw=true)



- **Install HMA**

   Select the directory where you stored the HMA apk and install it

   ![](image/HMA6.jpg?raw=true)

   After install is complete you should see a notification in the notification bar... pull down your notification bar and tap the **Xposed Module Is Not Activated Yet** notification

   ![](image/HMA7.jpg?raw=true)

   When the HMA app opens tap to toggle the **Enable Module** to **On**... make sure the **ONLY** scope that HMA is applied to is **System Framework**, then tap the gear icon towards the bottom right to go to HMA's Settings

   ![](image/HMA8.jpg?raw=true)


- **Configure HMA**
 
   When the **Settings** screen opens, tap on **Template Manage**

   ![](image/HMA9.jpg?raw=true)

---

   For instuctions on how to create a blacklist or whitelist template:
- [Create a blacklist template](BlackList.md)
- [Create a whitelist template](WhiteList.md)

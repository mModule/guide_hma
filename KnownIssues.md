# Known/Suspected Issues:

- ## **HMA is still detected by X detection app: (Blacklist Mode)**
   You may need to activate Vold App Data Isolation - Be aware a couple of people have reported that toggling this on has ended in tears for them, these people though have non-standard setups, using modules and apps which i and most people dont run and wouldnt recommend, and so therefore their experiences may be due to changes they have made to their systems outside the scope of this guide. 
 
   The following issues were highlighted, thanks **stillhard**

   - https://github.com/Dr-TSNG/Hide-My-Applist/issues/253
   - https://github.com/Dr-TSNG/Hide-My-Applist/issues/247

   Now that youve been warned, should you wish to enable Vold App Data Isolation (Note: Should ONLY be used in Blacklist Mode, NOT Whitelist Mode):

   From the HMA home screen: 

   ![](image/HMA14.jpg?raw=true)

   - Tap **Settings** (gear icon in bottom right) 
   - Scroll to **Module** section 
   - Tap **Data Isolation**

   ![](image/VOLD1.jpg?raw=true)

   - Tap to toggle **Vold App Data Isolation** to **ON**

   ![](image/VOLD2.jpg?raw=true)

   - Tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
   - Reboot device 
---

Continue to :<br>
[Return to Home](README.md)

Jump to :<br>
[Install LSPosed] - [Configure BlackList Mode] - [Configure WhiteList Mode] - [Test HMA] - [Backup and Restore]<br>

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
[Known Issues]: nownIssues.md

[Magisk Pages]: MagiskTOC.md
[Magisk USNF]: Magisk-SafetyNet-Fix.md
[PlayIntegrity]: Integrity-Check.md
[MagiskHide]: Magisk-Hide.md

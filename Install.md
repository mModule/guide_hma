# Installing and activating HMA.

Download (or copy) the HMA apk file to your device.<br>

Open your favorite file manager and navigate the directory where you stored the HMA apk file.
1. Select the the HMA apk file and install it.

![](image/HMA01.jpg?raw=true)

When the install is complete, you will see a new notification in the notification bar.

Pull down your notification bar.

1. Select the <b>Xposed Module Is Not Activated Yet</b> notification.

![](image/HMA02.jpg?raw=true)

LSPosed module manager will open to the HMA app.<br>

Activate HMA and then open HMA's settings (Home screen).
1. Turn on the <i>Enable module</i> toggle.
2. Select <b>only</b> <i>System Framework</i> for the scope that HMA is applied to.
3. The gear icon towards bottom right will take you into HMA's Home screen.

![](image/HMA03.jpg?raw=true)


## Configure HMA

After selecting the gear icon to open HMA, you will be able to setup and configure HMA.

![](image/HMA00.jpg?raw=true)

This is where you create/maintain templates for hiding apps and manage what apps the hiding is applied to.<br>
There are two options for hiding, they are exact opposites of each other.<br>
- BlackList mode will allow an app to find what ever other app it looks for.<br>
  <i>Only hiding the apps you choose to be hidden.</i>
- WhiteList mode will block an app from finding any other app it looks for.<br>
  <i>Only allowing the apps you choose to be found.</i>

If you have not read the differences between BlackList and WhiteList modes, please do so now.<br>
[Compare HMA Blacklist vs Whitelist Modes]

<i>You can use a mix of both BlackList and WhiteList modes.</i>

---

Continue to :<br>
[<b>Create a blacklist template</b>](BlackList.md)<br>
or<br>
[<b>Create a whitelist template</b>](WhiteList.md)<br>

Jump to :<br>
[Install LSPosed] - [Configure BlackList] - [Configure WhiteList] - [Test HMA] - [Backup and Restore]<br>

[<i>Return Home</i>](README.md)

<!--List of page links-->
[HMA Home]: (README.md)
[Install LSPosed]: Install-LSPosed.md
[Install HMA]: Install.md
[Compare HMA Blacklist vs Whitelist Modes]: BlacklistvsWhitelist.md
[Configure BlackList]: BlackList.md
[Configure WhiteList]: WhiteList.md
[Test HMA]: TestHMA.md
[Backup and Restore]: BackupAndRestore.md
[KnownIssues]: https://github.com/mModule/guide_hma/blob/master/KnownIssues.md

[Magisk Pages]: MagiskTOC.md
[Magisk USNF]: https://github.com/mModule/guide_hma/blob/master/Magisk-SafetyNet-Fix.md
[PlayIntegrity]: https://github.com/mModule/guide_hma/blob/master/Integrity-Check.md
[MagiskHide]: https://github.com/mModule/guide_hma/blob/master/Magisk-Hide.md

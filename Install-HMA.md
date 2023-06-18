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

<i>Note: You can use a mix of both BlackList and WhiteList modes.</i>

---

Continue to :<br>
[<b>Configure Blacklist Mode</b>](BlackList.md)<br>

[<b>Configure Whitelist Mode</b>](WhiteList.md)<br>

Jump to :<br>
[Install LSPosed] - [Configure Blacklist Mode] - [Configure Whitelist Mode] - [Hide from Store] - [Testing HMA] - [Backup and Restore]<br>

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

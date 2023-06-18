# HMA Backup & Restore

To save time on future installs, you can backup HMA's config and restore it after a clean ROM flash or post factory reset

Backup:

- From the main HMA screen scroll down if need be (due to ad placement) and tap <b>Backup</b>.
- Locate where you want to save the <b>HMA_Config.json</b> (prenamed) file and then tap <b>Save</b>.
- Copy <b>HMA_Config.json</b> off device for safe keeping.

Restore:

- Copy <b>HMA_Config.json</b> onto device if needed.
- Run through the setup as above until you reach the main HMA window at the [<b>Configure HMA</b>](https://github.com/mModule/guide_hma/blob/master/Install.md#configure-hma) stage.
- From the main HMA screen scroll down if need be (due to ad placement) and tap <b>Restore</b>.
- Locate where you stored the <b>HMA_Config.json</b> (prenamed) file and then tap <b>Restore</b>.

   If using Blacklist mode:
     - If you rename (hide) the Magisk Manager app (and you should), you will need to add the (new) renamed Magisk Manager's app to the root blacklist template after restoring the HMA config.
     - From the main HMA screen, tap <b>Manage Template</b>.
     - Tap <b>root</b> template.
     - Tap <b>Edit List</b> (the first one) to the right of <b>X Apps Invisible</b>.
     - Scroll to find your renamed Magisk Managers app and select it.
     
 - Tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen.
 - Close out from HMA.
 - Reboot your device to activate HMA and the configuration you just restored.

---

Continue to :<br>
[<b>Return Home</b>](README.md)<br>

Jump to :<br>
[Install LSPosed] - [Install HMA] - [Compare HMA Blacklist vs Whitelist Modes] - [Configure Blacklist Mode] - [Configure Whitelist Mode] - [Hide from Store] - [Testing HMA]<br>


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

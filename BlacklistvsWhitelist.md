# Blacklist vs Whitelist mode

## Blacklist mode (with template)

Uses a blacklist template (in the Template Manage section), containining those apps and modules (magisk, lsposed/xposed modules and associated apps) you wish you hide from a list of apps you select in the App Manage section.

The "traditional" mode, and mode the author recommends is Blacklist mode. Its the way most of us have used HMA. Whitelist mode however remains an option for those who want to try, or use it. Personally i (sydney73/adrianmmiller) have tried both modes, and for me, blacklist mode remains my choice. During whitelist mode testing i had issues with some apps that i use, but your mileage may vary, and this isnt meant to discourage anyone, but just as a heads up that you may experience issues using whitelist mode. 

Meanwhile zgfg, who first got myself (and others) into HMA has moved to using the Whitelist mode...and others have advocated it to be added to the guide

So clearly its a personal choice, and one that you may evolve to using over time

If you get stuck i recommend Blacklist mode as a fallback as its the mode most of us have used longest, and whose mode least hurts (at least) my head....

Note: If you do decide to change modes, please remember to clear data for any of the various root testing apps you may use, as failure to do so may use cached data and not be giving you an accurate reading


## Whitelist mode (no template)

(Generally) Uses enabling/toggling of Hide, Whitelist Work Mode and Exclude System Apps, ie. apps you wish to keep visible/accessible to other apps


Each mode has its pros and cons. This table aims to simply those. 

||Blacklist|Whitelist (no template)|
|---|---|---|
| Setup (Template Manage)|Y|N|
| Setup (App Manage)|Y|Y|
|Maintenance (new lsposed module/root related app install)|Y - Add in an existing Template only|N|
|Maintenance (new root sensitive app install)|Y - Configure in App Manage|Y - Configure in App Manage|


### A quick word on Whitelist (with Template) mode
It's possible to also have a setup whereby you use a whitelist with a template, containing those apps you wish other apps to be able to find, but so far no one seems to have found a compelling reason to use this....so of course the moment this goes live, i'll get an email...

---

Continue to :<br>
[<b>Return to <i>Installing and activating HMA</i></b>](Install.md)<br>

Jump to :<br>
[Install LSPosed] - [Install HMA] - [Configure BlackList Mode] - [Configure WhiteList Mode] - [Test HMA] - [Backup and Restore]<br>

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

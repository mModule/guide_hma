# Shamiko

I wanted to assume that by the time people made it to trying HMA, they would have an understanding of Deny List (& Shamiko) setup already, but a request was made to please expand/better explain this section of the guide.

### Deny List & Shamiko
 
  Native Magisk DenyList in Official Magisk (really a tool for developers/ researchers, it will revert/prevent Magisk modifications in selected processes) should be swapped for proper root hiding (ie. hides root traces w/o preventing Magisk modifications, eg injecting into apps zygote using Zygisk based modules). The go-to hiding solution is currently LSPosed teams Shamiko.

  A Quick guide on Deny List setup:

  - **Before** installing Shamiko, you should add any root senstive apps (banking/security apps etc) to your Deny List (please do NOT add ALL apps, or all google apps...)
  **Note:** These apps will generally also be the ones you will add to HMA's Blacklist, **if** using Blacklist Mode
  - **Disable** Enforce Deny List in Magisk Managers settings
  - Download and install Shamiko
  - Reboot

  **Please Note:**  Methods used to pass Integrity Check, and for extra 'root-trace' hiding, and therefore referenced modules like Shamiko, may change at any time, so please visit and watch the following XDA threads:
   - **Universal SafetyNet Fix:** https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-3-1.4217823/
   - **Magisk - The Age Of Zygisk:** https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877/

## Further methods to attempt to increase hiding

- A renamed/obfuscated Magisk App (I rename mine 'App', because im lazy and it puts it at the top of the App list when I'm adding it (using blacklist mode) to HMA both during setup and after restoring HMA config after a new ROM flash/factory reset, and HMA installation.)

---

Continue to :<br>
[<b>Return Home</b>](Magisk.md)

Jump to :<br>
[SafetyNet-Fix] - [PlayIntegrity]

[<i>Return to the HMA Guide</i>](README.md)

<!--List of page links-->
[HMA Home]: (README.md)
[Install LSPosed]: Install-LSPosed.md
[Install HMA]: Install.md
[Compare HMA Blacklist vs Whitelist Methods]: BlacklistvsWhitelist.md
[Configure BlackList]: BlackList.md
[Configure WhiteList]: WhiteList.md
[Test HMA]: TestHMA.md
[Backup and Restore]: BackupAndRestore.md
[KnownIssues]: https://github.com/mModule/guide_hma/blob/master/KnownIssues.md

[Magisk]: Magisk.md
[SafetyNet-Fix]: https://github.com/mModule/guide_hma/blob/master/Magisk-SafetyNet-Fix.md
[PlayIntegrity]: https://github.com/mModule/guide_hma/blob/master/Integrity-Check.md
[Shamiko]: https://github.com/mModule/guide_hma/blob/master/Magisk-Shamiko.md

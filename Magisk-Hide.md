# Setting Up A Magisk Installation That Hides Root From Apps

I wanted to assume that by the time people made it to trying HMA, they would have an understanding of Deny List (& Shamiko) or MagiskHide (or SuList) setup already, but a request was made to please expand/better explain this section of the guide.

<ins>Methods:</ins>

- $\textcolor{orange}{\textsf{Deny List \\& Shamiko via Official Magisk:}}$
 
  Native Magisk DenyList in Official Magisk should be swapped for proper root hiding via (currently) Shamiko

  A Quick guide on Deny List setup:

  - **Before** installing Shamiko, you should add any root senstive apps (banking/security apps etc) to your Deny List (please do NOT add ALL apps, or all google apps...)
  - **Disable** Enforce Deny List in Magisk Managers settings
  - Download and install Shamiko
  - Reboot

   **Shamiko Download Link:** [here](https://github.com/LSPosed/LSPosed.github.io/releases)


- $\textcolor{orange}{\textsf{MagiskHide or SuList via Magisk Delta:}}$

  Either via MagiskHide or SuList (each has its benefits - not discussed here and best handled in Magisk Deltas own thread linked above)

  For the purposes of the guide, we will assume MagiskHide

  Quick guide on MagiskHide setup: 
  - You should add any root senstive apps (banking/security apps etc) to your MagiskHide List (please do NOT add ALL apps)
  - Reboot

  **Please Note:**  Methods used to pass Integrity Check, and for extra 'root-trace' hiding, and therefore referenced modules like Shamiko, may change at any time, so please visit and watch the following XDA threads:
   - **Universal SafetyNet Fix:** https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-3-1.4217823/
   - **Magisk - The Age Of Zygisk:** https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877/
   - **Magisk Delta:** https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/


<ins>Further methods to attempt to increase hiding:</ins>

- A renamed/obfuscated Magisk App (I rename mine 'App', because im lazy and it puts it at the top of the App list when I'm adding it to HMA both during setup and after restoring HMA config after a new ROM flash/factory reset, and HMA installation.)

---

Continue to :


Jump to :<br>
[PlayIntegrity] - [MagiskHide]<br>

[<i>Return Home</i>](MagiskTOC.md)

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

[Magisk Pages]: MagiskTOC.md
[Magisk USNF]: https://github.com/mModule/guide_hma/blob/master/Magisk-SafetyNet-Fix.md
[PlayIntegrity]: https://github.com/mModule/guide_hma/blob/master/Integrity-Check.md
[MagiskHide]: https://github.com/mModule/guide_hma/blob/master/Magisk-Hide.md

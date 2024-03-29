# Shamiko

This module <b>requires</b> <i>Zygisk</i> to be enabled and active in Magisk.<br>

From the Magisk Home tab:
- Select Settings (gear icon on the top line).
- Next scroll down to the Magisk section, and make sure Zygisk is enabled

![](image/magiskmainsettings.jpg?raw=true) ![](image/magiskzygiskenabled.jpg?raw=true)

This module uses Magisk's <i>DenyList</i> for configuration only as a convenient means for selecting processes for inclusion. Note that Denylist will <u>actually</u> be disabled and its 'hijacked' list will now really function as a 'Hidelist'.

This is important to understand since the functions or a Hidelist and Magisk's Denylist are very different; Hidelist modules hide many traces of root and device modification not handled by Denylist, while Denylist simply denies/reverts MAGISK modifications in listed processes (and will therefore actually break modules that inject into such processes)
including superuser access/grants.<br>

## Installing the module.
Download (or copy) the Shamiko zip file to your device.<br>
1. Open the Magisk app and switch to the Modules section at bottom of the screen.
2. Select <i><b>Install from storage</b></i> at the top of screen.

 ![](image/shamiko01.jpg?raw=true)

1. Select the directory where you stored the Shamiko zip file.
2. Select the zip file to install it.

 ![](image/shamiko02.jpg?raw=true)

The Shamiko module will be installed.<br>
1. Select <i><b>Reboot</b></i> to reboot your device.

 ![](image/magiskmodulereboot.jpg?raw=true)

After your device restarts, the module will be active.<br>

  ![](image/shamiko03.jpg?raw=true)
  
  
## Configuration.
The configuration is set using Magisk's DenyList.<br>
<i>Note: This module requires <b>Enforce Denylist</b> to be turned <b>off</b>.</i>

Select settings (gear icon on the top line).

 ![](image/magiskmainsettings.jpg?raw=true)

Scroll down to the Magisk section

1. You should of course already have Zygisk enabled
2. Make sure Enforce DenyList is disabled
3. Tap Configure DenyList

 ![](image/shamiko04.jpg?raw=true)

Add the apps you need to Magisk's DenyList.

 ![](image/shamiko05.jpg?raw=true)

You should add root sensitive apps (banking/security apps etc) to the DenyList.<br>
  <i><b>Note:</b> These apps will generally also be the ones you will add to HMA's Blacklist, <b>if</b> using Blacklist Mode.<br>
  Do <b>NOT</b> add all apps, or even all google apps. Indiscriminate use can break functions like webview...<br>
  <b>Only add what is necessary.</b></i>

---

### Further methods to (attempt) increase hiding

A renamed/obfuscated Magisk App.<br>
  <i>I rename mine 'App', because i am lazy and it puts it at the top of the App list when I'm adding it (using blacklist mode) to HMA both during setup and after restoring HMA config after a new ROM flash/factory reset, and HMA installation.</i>

<b>Note:</b><br>
Methods used to pass Play Integrity and for extra 'root-trace' hiding, therefore referenced modules like Shamiko, may change at any time.<br>
Please visit and watch the following XDA threads:
   - [Play Integrity Fix](https://xdaforums.com/t/module-play-integrity-fix-safetynet-fix.4607985)
   - [Universal SafetyNet Fix](https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-3-1.4217823)
   - [Magisk - The Age Of Zygisk](https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877)

---

Continue to :<br>
[<b>Return Home</b>](Magisk.md)

Jump to :<br>
[SafetyNet-Fix] - [PlayIntegrity]

[<i>Return to the HMA Guide</i>](README.md)

<!--List of page links-->
[Magisk]: Magisk.md
[PlayIntegrity]: Magisk-Integrity.md
[SafetyNet-Fix]: Magisk-SafetyNet-Fix.md
[Shamiko]: Magisk-Shamiko.md

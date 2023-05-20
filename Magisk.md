# Magisk Configuration

Minimal set of instructions to configure Magisk to pass Play Integrity and hide root from apps.

## Overview
This is a brief guide using the official Magisk build(s) to:<br>

1) Pass Play Integrity.
2) Hide Root From Apps.

This is done by using two modules.<br>
SaftyNet-Fix to pass Play Integrity and Shamiko to hide root from applications that you choose.<br>

Note:<br>
>This is not to discourage use of or disparage those who use other variants (forks) of Magisk or alternative integrity verdict or root hiding solutions.<br>
>Alpha and Delta, have been appreciated and served their purpose, particularly in the gap period where MagiskHide (the original root hiding method) was removed, and an alternate was found.<br>
>As there are often rapid changes in Alpha/Delta forks, a decision was made for simplicty's sake, to concentrate on using the official Magisk build(s) in this brief guide.<br>

This guide will not cover the installation of Magisk as that can vary greatly with device or OS.<br>
Installation steps are best handled in the existing XDA threads for Magisk, or on occasion in your devices specific XDA threads on how to root x device.<br>

<i>For more information on installing Magisk, current issues and support, please see the xda-developers links below.</i><br>

<b>Do not post Magisk issues here.<br>
They will be closed without reply.</b><br>

## Requirement(s)
- Magisk
- SafetyNet Fix
- Shamiko

## Download Links
[Magisk](https://github.com/topjohnwu/Magisk#downloads) - Official.<br>

Modules:
- [SafetyNet Fix (USNF)](https://github.com/kdrag0n/safetynet-fix/releases) - Official.
- [SafetyNet Fix (USNF)](https://github.com/Displax/safetynet-fix/releases) - <i>Modified by <b>Displax</b></i>.<br>
- [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases)

<i><b>Note: At time of writing (06/02/2023 DD/MM/YYYY)</b> Kdrag0n's official USNF 2.4.0 does have some issues.<br>
If you experience any, please use Displax's 2.3.1 Mod 2.1 (or better) instead.</i><br>

## Pages (How To)
- [SafetyNet Fix](Magisk-SafetyNet-Fix.md)
- [Integrity Check](Integrity-Check.md)
- [Shamiko](Magisk-Shamiko.md)

---

[<i>Return to the HMA Guide</i>](README.md)

---

### xda-developers
- [Magisk Magisk General Support / Discussion:](https://forum.xda-developers.com/t/magisk-general-support-discussion.3432382)
- [[Discussion] Magisk - The Age of Zygisk.:](https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877)
- [MAGISK MODULE ❯ Universal SafetyNet Fix 2.4.0:](https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-4-0.4217823)


## Credits

- John Wu and team for all things [Magisk](https://github.com/topjohnwu/Magisk).
- kdrag0n (and contributors) for SaftyNet Fix.
- The LSPosed team for Shamiko.

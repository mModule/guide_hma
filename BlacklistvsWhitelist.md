# Blacklist vs Whitelist mode

The "traditional" method, and method the author recommends is Blacklist mode. Its the way most of us have used HMA for. Whitelist mode however remains an option for those who want to try, or use it. Personally i (sydney73/adrianmmiller) have tried both methods, and for me, blacklist mode remains my choice. During whitelist mode testing i had issues with some apps that i use, but your mileage may vary, and this isnt meant to discourage anyone, but just as a heads up that you may experience issues using whitelist mode. Meanwhile zgfg, who first got myself (and others) into HMA has moved to using the Whitelist method...

So clearly its a personal choice, and one that may evolve over time

If you get stuck i recommend Blacklist mode as a fallback as its the method most of us have used longest, and whose method least hurst (at least) my head....

Note: If you do decide to change methods, please remember to clear data for any of the various root testing apps you may use, as failure to do so may use cached data and not be giving you an accurate reading

## Blacklist mode

Uses a blacklist template (in the Template Manage section), containining those apps and modules (magisk, lsposed/xposed modules and associated apps) you wish you hide from a list of apps you select in the App Manage section.

## Whitelist mode (no template)

(Generally) Uses enabling/toggling of Hide, Whitelist Work Mode and Exclude System Apps per app you wish to hide from other apps


Each mode has its pros and cons. This table aims to simply those. 

||Blacklist|Whitelist (no template)|
|---|---|---|
| Setup (Template Manager)|Y|N|
| Setup (App Manage)|Y|Y|
|Maintenance (new lsposed module install)|Y - Template modification ONLY|Y - App Manage section ONLY|
|Maintenance (new root sensitive app install)|Y - App Manage selection ONLY|N|


### A quick word on Whitelist (with Template) mode
It's possible to also have a setup whereby you use a whitelist with a template, containing those apps you wish other apps to be able to find, but so far no one seems to have found a compelling reason to use this....so of course the moment this goes live, i'll get an email...

---

Continue to :

- [Configure HMA using the blacklist method](BlackList.md)
- [Configure HMA using the whitelist method](WhiteList.md)
- [Return Home](README.md)

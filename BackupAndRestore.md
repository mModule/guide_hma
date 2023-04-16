# HMA Backup & Restore

To save recreating the root blacklist template and apps list, you can backup HMA's config and restore it after a clean ROM flash or post factory reset

Backup:

- From the main HMA screen scroll down if need be (due to ad placement) and tap **Backup**
- Locate where you want to save the **HMA_Config.json** (prenamed) file and then tap **Save**
- Copy **HMA_Config.json** off device for safe keeping

Restore:

- Copy **HMA_Config.json** onto device if needed
- Run through the setup as above until you reach the main HMA window at the [**Configure HMA**](https://github.com/mModule/guide_hma/blob/master/Install.md#configure-hma) stage
- From the main HMA screen scroll down if need be (due to ad placement) and tap **Restore**
- Locate where you stored the **HMA_Config.json** (prenamed) file and then tap **Restore**
- If you rename (hide) the Magisk Manager app, and you should, you will need to add the (new) renamed Magisk Manager's app to the root blacklist template after restoring the HMA config:
   - From the main HMA screen, tap **Manage Template**
   - Tap **root** template
   - Tap **Edit List** (the first one) to the right of **X Apps Invisible**
   - Scroll to find your renamed Magisk Managers app and select it
   - Tap the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
   - Close out from HMA
   - Reboot your device to activate HMA and the configuration you just restored

---

Continue to :
- [Return Home](README.md)

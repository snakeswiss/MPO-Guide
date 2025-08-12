![PSVita Logo](../assets/PlayStation_Vita_logo.svg.png)
# (real hardware)

## Requirements
- A **PS Vita** with **Custom Firmware** (e.g. HENkaku / ENSO / h-encore² / VitaDeploy / etc..)
- **Adrenaline** installed (eCFW PSP which simulates the PSP environment to launch the game with the plugin `savempo` that is necessary)
- A memory stick with at least 1 GB free
- A legally dumped copy of MPO / MPO+ in ISO or CSO format to launch with **Adrenaline**

---

## Installation Steps

1. Download the Plugins savempo: [Plugin savempo](https://github.com/snakeswiss/MPO-Guide/raw/main/assets/savempo.zip)
2. Extract the files to `ux0:/pspemu/seplugins`
3. Edit `ms0:/seplugins/game.txt` and add the line `ms0:/seplugins/savempo_boot.prx 1`

---

## Recommended Settings
To improve compatibility and loading times:

1. Start the **Recovery Menu** (Hit select while in the XMB menu of PSP Adrenaline):
2. Go to:
   - `Configuration > UMD Mode`
   - Set to `M33 Driver` for better compatibility
3. Disable plugins you don’t need except for `savempo_boot.prx [GAMES]` that must stay **Enabled**.

![PSP Logo](../assets/Psp-logo.png)
# (real hardware)

## Requirements
- A PSP with custom firmware (e.g. PRO-C2, ME, or Infinity) (PSP Street E-1000 isn't supported as it doens't have a wireless card)
- A memory stick with at least 1 GB free
- A legally dumped copy of MPO / MPO+ in ISO or CSO format or original UMD

---

## Installation Steps

1. Download the Plugins savempo: [Plugin savempo)](https://github.com/snakeswiss/MPO-Guide/raw/main/assets/savempo.zip)
2. Extract the files to ```ms0:/seplugins```
3. Edit ```ms0:/seplugins/game.txt``` and add the line : ```ms0:/seplugins/savempo_boot.prx 1```

---

## Recommended Settings
To improve compatibility and loading times:

1. Reboot PSP into **Recovery Menu**:
   - Hold `R` while powering on the console.
2. Go to:
   - `Configuration > UMD Mode`
   - Set to `M33 Driver` for better compatibility
3. Disable plugins you don’t need except for `savempo_boot.prx [GAMES]` that must stay **Enabled**.

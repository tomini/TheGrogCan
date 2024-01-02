# The Grog Can mod

![Icon](https://raw.githubusercontent.com/tomini/TheGrogCan/main/icon.png) ![Grogs in hand](https://raw.githubusercontent.com/tomini/TheGrogCan/main/grogs_in_hand_small.jpg)
 
Replaces the Red Soda item with a Grog from Cold Ones. (peach, grape, lemon, random at launch)

Funny mod video --> **[HERE](https://youtu.be/syAzsMhn8B4)**

## Config

You can change the behaviour of this mod after first launch with the mod:

1. Inside `.\BepInEx\config` folder there is `TheGrogCan_by_Tomini.cfg` file. Open it.
2. At the end there is `TextureChoice = 0`. Change it to your liking. (default is `0`)
    - `0` -> Random at start-up
    - `1` -> Grog Grape
    - `2` -> Grog Peach
3. Enjoy your Grog!

## &#128736; Mod Manager Friendly &#128736;
![r2modman](https://raw.githubusercontent.com/ebkr/r2modmanPlus/master/src/assets/icon/96x96.png) &  ![Thunderstore](https://www.overwolf.com/oneapp/assets/img/app-page/thunderstore-mod-manager/app-icon.webp)

## Manual installation

1. Download and unzip
2. Move `BepInEx` folder to the Lethal Company folder
    (e.g. `C:\Program Files (x86)\Steam\steamapps\common\Lethal Company`)
3. You can check if you did it right:
    1. Look up mod files:
        - inside `.\BepInEx\plugins` folder there is `TheGrogCan_by_Tomini.dll` file
    2. Look at BepInEx log at start-up:
        ```
        [Info   :   BepInEx] Loading [TheGrogCan_by_Tomini 1.0.4]
        [Info   :TheGrogCan_by_Tomini] Loaded asset bundle
        [Info   :TheGrogCan_by_Tomini] Configuration: Random
        [Info   :TheGrogCan_by_Tomini] Selected texture: grog_lemon
        [Info   :TheGrogCan_by_Tomini] Plugin TheGrogCan_by_Tomini is loaded!
        ```

## Future of this mod

- ~~add Lemon Ice Grog~~ &#10004;
- add custom sound(s)
- change item name
- texture randomization within session

## Incompatible mods

While this mod doesn't break other mods, it can't replace the texture if these mods are used to spawn scrap

- GameMasterDevs-GameMaster
- femboytv-LethalAdjustments

## Thanks!

Thank you, [KlutzyBubbles](https://thunderstore.io/c/lethal-company/p/KlutzyBubbles/) for the [VBCan mod](https://thunderstore.io/c/lethal-company/p/KlutzyBubbles/VBCan/).

Big thanks to **willis81808** for their invaluable assistance and warm welcome! As a first-time game modder, having someone so kind and helpful made a world of difference. 

## Contact

Discord: `tomini`
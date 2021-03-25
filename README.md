# **Skill Toggles**

> A [PythonSDK] mod for [Borderlands 2][borderlands2] to give Deathtrap its own configurable shield from the inventory of Gaige.

- [Discord][discord]
- PythonSDK: `v0.7.9`
- Mod Menu: `v2.4`

---

## **📎 Features**
- Deathtrap can use its own shield and no longer shares the shield with Gaige
- you can define which shield to use in the inventory
- configurable hotkey


## **📑 Notes**
- this is a [PythonSDK] mod, you **can't** install it with BLCMM
- this mod needs the [EridiumLib] in order to run
- since this is often not the case with SDK mods: yes, this has multiplayer support
- the default behaviour of the skill applies and the shield of Gaige will be shared when:
  - you didn't unlock the skill sharing ability
  - you don't set a Deathtrap shield
  - the shield level is too high; you need to be able to equip it too
  - you equip the Deathtrap shield to Gaige
- the Deathtrap shield will lose its status when:
  - you set a new Deathtrap shield while already having one
  - you equip the Deathtrap shield to Gaige
  - you throw the Deathtrap shield on the ground
  - another character that is not a Mechromancer puts it in their inventory
- you can only set one Deathtrap shield at a time
- only Mechromancers can set Deathtrap shields and see the status
- the hotkey to set the Deathtrap shield can be modified in the modded keybinds
- if you have a Deathtrap shield set, you won't be able to edit your save game in the SaveGame Editor unless you rejoin the game and remove the shield status, this can't be fixed


## **🔧 Installation**
1. download the latest **release** of this mod from [releases]
2. download the latest **release** of the EridiumLib from [here][eridiumlib_releases]
3. extract it to:
   - `Borderlands 2\Binaries\Win32\Mods`
4. activate the mod in the Mod Menu within the game


## **⏰ Changelog**
Everything related to versions and their release notes can be found in the [changelog].


## **🎓 License**
This project is licensed under the [GNU GPL v3.0][license].


<!-- Links -->
[pythonsdk]: http://borderlandsmodding.com/sdk-mods/
[borderlands2]: https://store.steampowered.com/app/49520/Borderlands_2/
[discord]: https://discordapp.com/invite/Q3qxws6
[releases]: https://github.com/RLNT/bl2_deathtrapshield/releases
[eridiumlib]: https://github.com/RLNT/bl2_eridium
[eridiumlib_releases]: https://github.com/RLNT/bl2_eridium/releases
[changelog]: CHANGELOG.md
[license]: LICENSE
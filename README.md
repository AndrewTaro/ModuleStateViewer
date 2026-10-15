# Module State Viewer
This modification allows you to monitor the detailed status of your main battery and torpedoes.

You can press Alt-key to display all the module states.  
The armament icons always become visible when incapacitated.
- Remaining HP
- Time to Restore

![image](https://github.com/user-attachments/assets/963789ea-f0b3-4f15-8145-87a6f192efb9)
![image](https://github.com/user-attachments/assets/fff63263-1562-4a62-b65a-233fa6a4915c)


### Observer Mode:
If you are an observer in the training room, you can target a ship by simply looking at it. Then the mod shows the module status of the targeted ship.

A panel shows the whole ship at a glance: a hull outline with every armament at its real position.
- Main battery and torpedo launchers: icon, remaining HP in percent, and the time to restore while incapacitated.
- Secondary battery: a dot colored by its state.
- Engine and steering gear: an icon with the time to restore appears under the hull while one is knocked out.

The icons on the ship itself are shown for the main battery and torpedo launchers only. They appear while the ALT key is held, or while the armament is incapacitated. If the target is far away, the remaining HP and critical timers are not rendered on them.

### Settings:
The panel can be dragged anywhere on the screen. The following are available in the TTaro Mod Utils settings window:
- Disable drag and drop
- Display mode: off, on, or only while the ALT key is held
- Scale
- Font size

# Requirements
You must install the following for this mod to work:
- [TTaro Mod Utils](https://github.com/AndrewTaro/TTaroModUtils): the settings of this mod live there.
- [ModForge](https://github.com/AndrewTaro/ModForge): mounts the mod into the battle UI. One copy serves every mod that uses it.

# Install
1. Download a zip.
2. Unzip the archive and you should get `gui`, `PnFMods`, `ModSchemas`, `ForgeBlueprints` folders, and `PnFModsLoader.py`.
3. Move them to `(wows)/bin/(latest_number)/res_mods/`. So the path will look like `res_mods/PnFModsLoader.py`, etc.
4. Done!

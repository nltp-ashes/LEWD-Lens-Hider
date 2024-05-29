# LEWD LENS HIDER [![License](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

---

Script used to selectively hide a bone on the weapon's HUD model when aiming down sights.

---

### ABOUT

Script used to selectively hide a bone on the weapon's HUD model when aiming down sights.

The lewd_lens_hider.script will look for specific config lines :

- **Name**          : `lewd_lens_hide_enabled`  
  **Presence**      : Required  
  **Default value** : N/A  
  **Description**   : Master safe, to enable/disable the script

- **Name**          : `lewd_lens_hide_bone`  
  **Presence**      : Required  
  **Default value** : N/A  
  **Description**   : Name of the bone to hide

- **Name**          : `lewd_lens_hide_delays`  
  **Presence**      : Optional  
  **Default value** : `0.0,0.0`  
  **Description**   : Delay (in sec) before showing/hiding the bone when aiming out/in

- **Name**          : `lewd_lens_hide_aim_mode`  
  **Presence**      : Optional  
  **Default value** : `true,true,true`  
  **Description**   : Whether to hide bone in respectively normal, alt and gl modes

---

### REQUIREMENTS

The following are **absolutely required** for the script to work :
1. [S.T.A.L.K.E.R. Anomaly 1.5.2](https://www.moddb.com/mods/stalker-anomaly/downloads/stalker-anomaly-151-to-152);
2. [DLTX and DXML](https://github.com/themrdemonized/STALKER-Anomaly-modded-exes).

---

### INSTALLATION

To **install** the addon :
1. Download and install the requirements;
2. Download this addon;
3. Merge the contents of the gamedata folder with your game's folder of the same name;
   - Either with a mod manager JSGME/MO2 (highly recommended);
   - Or manually (highly unrecommended).

To **update** the addon :
1. Delete the files from the previous version;
   - By disabling the addon in your mod manager, and then deleting the files;
   - Or by deleting the files one by one if you added them manually;
2. Add in the new files from the new version;
   - Either with a mod manager JSGME/MO2 (highly recommended);
   - Or manually (highly unrecommended).

To **uninstall** the addon :
1. Simply remove the files added by the addon.

---

### CHANGELOG

For past updates, please refer to the description of each release, in the [releases tab](https://github.com/nltp-ashes/LEWD-Lens-Hider/releases).

---

### LICENSE

This script is licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

This means you're allowed to redistribute and/or adapt the work, as long as you respect the following criteria :
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

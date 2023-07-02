Derail Valley uses BepInEx for modding.
BepInEx is a mod loader and modding framework for Unity games.
It is required for all mods to work.


Installing BepInEx
------------------

1. Download the latest version of BepInEx v5.  
   You can get it from [their GitHub][bepinex-releases], or by clicking [this][bepinex-download].

2. Find your Derail Valley installation folder.  
   If you aren't sure where it is, you can find it by right-clicking Derail Valley in your Steam library, clicking `Manager`, then clicking `Browse Local Files`.  
   ![Steam Browse Files][steam-browse-files]

3. Extract the contents of the BepInEx archive into the Derail Valley folder.  
   This can be done by simply dragging the contents of the archive into the folder.  
   ![Extract BepInEx][extract-bepinex]  
   If asked to overwrite files, say yes.  
   ![Replace Files Dialog][replace-files]


Installing Configuration Manager
--------------------------------

By default, BepInEx doesn't have a way to configure mods in-game.
Configuration Manager is a mod that adds a configuration menu to the game.

1. Download the latest version of Configuration Manager.  
   You can get it from [their GitHub][configurationmanager-releases], or by clicking [this][configurationmanager-download].

2. Extract the contents of the Configuration Manager archive into the Derail Valley folder.  
   This is exactly the same process as installing BepInEx.  
   ![Extract Configuration Manager][extract-configurationmanager]

3. Start the game, then close it. This is required to generate the configuration file.

4. Open the `BepInEx/config` folder in the Derail Valley folder, then open the `com.bepis.bepinex.configurationmanager.cfg` file with a text editor like Notepad.

5. Look for the line starting with `Show config manager`.
   By default, this is set to `F1`.
   ![Configuration Manager Default Keybind][configurationmanager-default-keybind]
   This conflicts with a Derail Valley keybind, so you'll need to change it to something else like `F10`.
   ![Configuration Manager New Keybind][configurationmanager-new-keybind]

6. Save the file, and you're good to go!


[bepinex-releases]: https://github.com/BepInEx/BepInEx/releases/latest/
[bepinex-download]: https://github.com/BepInEx/BepInEx/releases/latest/download/BepInEx_x64_5.4.21.0.zip
[configurationmanager-download]: https://github.com/BepInEx/BepInEx.ConfigurationManager/releases/latest/download/BepInEx.ConfigurationManager_v18.0.zip
[configurationmanager-default-keybind]: ../assets/configurationmanager-default-keybind.png
[configurationmanager-new-keybind]: ../assets/configurationmanager-new-keybind.png
[configurationmanager-releases]: https://github.com/BepInEx/BepInEx.ConfigurationManager/releases/latest/
[extract-bepinex]: ../assets/extract-bepinex.png
[extract-configurationmanager]: ../assets/extract-configurationmanager.png
[replace-files]: ../assets/replace-files.png
[steam-browse-files]: ../assets/steam-browse-files.png

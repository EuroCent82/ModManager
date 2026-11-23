<p align="center">
  <img src="screenshot/banner-readme.jpg" alt="Mod manager" width="960">
</p>

<p align="center">
  <a href="https://github.com/EuroCent82/ModManager">GitHub</a>
  &nbsp;·&nbsp;
  <a href="https://pineloader.dev">pineloader.dev</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/EuroCent82/PineLoader">PineLoader</a>
</p>

<p align="center">
  Turns mods on and off in the settings.<br>
  The key has its own row.
</p>

<p align="center">
  <a href="https://github.com/EuroCent82/ModManager"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-EuroCent82%2FModManager-245C48?style=flat-square"></a>
  <a href="https://pineloader.dev"><img alt="pineloader.dev" src="https://img.shields.io/badge/site-pineloader.dev-D5B41A?style=flat-square"></a>
  <a href="LICENSE"><img alt="Apache License 2.0" src="https://img.shields.io/badge/license-Apache%202.0-D5B41A?style=flat-square"></a>
  <img alt="Version 1.0.2" src="https://img.shields.io/badge/version-1.0.2-245C48?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/EuroCent82/ModManager/releases/latest"><img alt="Download 1.0.2" src="https://img.shields.io/badge/download-1.0.2-D5B41A?style=flat-square"></a>
</p>

Mod Manager is an optional [PineLoader](https://github.com/EuroCent82/PineLoader) mod for Pionero Capital. It adds a **Mod-Manager** tab after Keyboard in the game's settings. Each loaded mod gets the same on/off bar the game uses for VSync, and a second row for its key. That key row uses the game's own key button.

Glovebox does not need this mod. Without Mod Manager, Glovebox still reads `Config/Glovebox.ini` and still opens on its key.

The pictures are the German game. The labels follow the language of the game.

## Settings

The Mod-Manager tab sits after Keyboard.

<p align="center">
  <img src="screenshot/settings.png" alt="Game settings, with the Mod-Manager tab after Keyboard" width="720">
</p>

## The switch

On and off use the same bar as VSync. In German the row reads Handschuhfach.

<p align="center">
  <img src="screenshot/mod-manager.png" alt="Handschuhfach switched on, with the key row set to K" width="770">
</p>

Off leaves the saved items where they are.

<p align="center">
  <img src="screenshot/glovebox-off.png" alt="Handschuhfach switched off" width="770">
</p>

## Key

The key row uses the game's own key button. Pressing it asks for any key.

<p align="center">
  <img src="screenshot/rebind-key.png" alt="The game asking for a key" width="720">
</p>

## Install

PineLoader has to be installed first. Close the game.

1. Download [Mod Manager 1.0.2](https://github.com/EuroCent82/ModManager/releases/latest). The file is `ModManager-1.0.2.zip`.
2. Copy the `ModManager` folder from that zip into `PineLoader/Mods`. The folder needs `ModManager.dll`.
3. Start the game from Steam.
4. Open Settings. The new tab sits after Keyboard.

The first time the tab is missing, start the game once through PineLoader so the menu file can be prepared, then open Settings again. A copy of the menu file is kept under `PineLoader/Cache/` before it is changed.

Switching a mod writes `Running` in that mod's ini. Choosing a key writes `Key`. The game's own graphics, sound, gameplay, and keyboard pages stay as they are.

## License

Apache License 2.0. See [LICENSE](LICENSE).

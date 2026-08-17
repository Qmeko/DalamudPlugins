# DalamudPlugins

[日本語](README.ja.md)

Custom Dalamud plugin repository for Qmeko plugins.

## Repository URL

```
https://raw.githubusercontent.com/Qmeko/DalamudPlugins/refs/heads/main/pluginmaster.json
```

## Install

1. Run `/xlsettings` and open the **Experimental** tab
2. Add the URL above under **Custom Plugin Repositories**
3. Enable it, save, then run `/xlplugins`

## Plugins

<!-- PLUGINS_TABLE_START -->
| Icon | Name | Description |
| ---- | ---- | ---- |
| | [ConditionCommandSender](https://github.com/Qmeko/ConditionCommandSender) | Log-trigger rules with tags, commands, waits, and Lua. EN/JA UI. |
| | [MateriaExtractor](https://github.com/Qmeko/MateriaExtractor) | Retrieve materia and meld from an exdreams share URL. |
| | [Doman Mahjong Solver Debug](https://github.com/Qmeko/FFXIV-AutoMahjongSolver) | Mortal / Akochan suggestions and auto-play. Mortal installs on first launch. |
| | [Smart Recipe Restock](https://github.com/Qmeko/SmartRecipeRestock) | Withdraw missing recipe materials from each retainer. |
<!-- PLUGINS_TABLE_END -->

## Umbra plugins

These are **not** installed from `/xlplugins`. Add the DLL in Umbra settings → **Custom Plugins**.

| Name | Description |
| ---- | ---- |
| [Umbra AutoRetainer](https://github.com/Qmeko/Umbra.AutoRetainer) | Toolbar widget that shows AutoRetainer retainer and submarine status (`R7\|20　M0\|4`). Click opens `/ays`. |

### Umbra AutoRetainer install

1. Install [Umbra](https://github.com/una-xiv/umbra) and [AutoRetainer](https://github.com/PunishXIV/AutoRetainer)
2. Build the project or copy `Umbra.AutoRetainer.dll`
3. In Umbra settings, enable **Custom Plugins** and add the DLL
4. Add the **AutoRetainer** widget to the toolbar

## Contact

GitHub: [Qmeko](https://github.com/Qmeko)

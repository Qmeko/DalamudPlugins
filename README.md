# DalamudPlugins

[日本語](#日本語)

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
2. In Umbra settings, open **Custom Plugins**
3. Set owner to `Qmeko` and repository to `Umbra.AutoRetainer`, then **Install**
4. Reload Umbra and add the **AutoRetainer** widget to the toolbar

Or download the zip from [Releases](https://github.com/Qmeko/Umbra.AutoRetainer/releases/latest) and add the DLL.

## Contact

Discord: q_u.s.a.

---

## 日本語

Qmeko プラグイン用のカスタム Dalamud リポジトリです。

### リポジトリURL

```
https://raw.githubusercontent.com/Qmeko/DalamudPlugins/refs/heads/main/pluginmaster.json
```

### インストール

1. `/xlsettings` を実行し、**試験的機能**タブを開く
2. **カスタムプラグインリポジトリ** に上の URL を追加する
3. 有効化して保存し、`/xlplugins` を実行する

### プラグイン

| Icon | Name | Description |
| ---- | ---- | ---- |
| | [ConditionCommandSender](https://github.com/Qmeko/ConditionCommandSender) | ログ条件でルールを実行。Wait / Command / Lua。UIは英日対応。 |
| | [MateriaExtractor](https://github.com/Qmeko/MateriaExtractor) | マテリア回収と exdreams 共有URLからの禁断支援。 |
| | [Doman Mahjong Solver Debug](https://github.com/Qmeko/FFXIV-AutoMahjongSolver) | Mortal／Akochanの判断で自動操作。Mortalは初回起動時に自動セットアップ。 |
| | [Smart Recipe Restock](https://github.com/Qmeko/SmartRecipeRestock) | 開いているレシピの不足材料を、各リテイナーから取り出す。 |

### Umbra プラグイン

こちらは `/xlplugins` からは入れません。Umbra の設定 → **Custom Plugins** に DLL を追加します。

| Name | Description |
| ---- | ---- |
| [Umbra AutoRetainer](https://github.com/Qmeko/Umbra.AutoRetainer) | ツールバーに AutoRetainer のリテイナー／潜水艦の状態を出します（`R7\|20　M0\|4`）。クリックで `/ays` を開きます。 |

#### Umbra AutoRetainer の入れ方

1. [Umbra](https://github.com/una-xiv/umbra) と [AutoRetainer](https://github.com/PunishXIV/AutoRetainer) を入れる
2. Umbra の設定で **Custom Plugins** を開く
3. オーナーに `Qmeko`、リポジトリ名に `Umbra.AutoRetainer` を入れて **Install**
4. Umbra を再読み込みし、ツールバーに **AutoRetainer** ウィジェットを足す

または [Releases](https://github.com/Qmeko/Umbra.AutoRetainer/releases/latest) から ZIP をダウンロードして、中の DLL を追加します。

### 連絡先

Discord: q_u.s.a.

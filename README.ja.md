# DalamudPlugins

[English](README.md)

Qmeko プラグイン用のカスタム Dalamud リポジトリです。

## リポジトリURL

```
https://raw.githubusercontent.com/Qmeko/DalamudPlugins/refs/heads/main/pluginmaster.json
```

## インストール

1. `/xlsettings` を実行し、**試験的機能**タブを開く
2. **カスタムプラグインリポジトリ** に上の URL を追加する
3. 有効化して保存し、`/xlplugins` を実行する

## プラグイン

| Icon | Name | Description |
| ---- | ---- | ---- |
| | [ConditionCommandSender](https://github.com/Qmeko/ConditionCommandSender) | ログ条件でルールを実行。Wait / Command / Lua。UIは英日対応。 |
| | [MateriaExtractor](https://github.com/Qmeko/MateriaExtractor) | マテリア回収と exdreams 共有URLからの禁断支援。 |
| | [Doman Mahjong Solver Debug](https://github.com/Qmeko/FFXIV-AutoMahjongSolver) | Mortal／Akochanの判断で自動操作。Mortalは初回起動時に自動セットアップ。 |
| | [Smart Recipe Restock](https://github.com/Qmeko/SmartRecipeRestock) | 開いているレシピの不足材料を、各リテイナーから取り出す。 |

## Umbra プラグイン

こちらは `/xlplugins` からは入れません。Umbra の設定 → **Custom Plugins** に DLL を追加します。

| Name | Description |
| ---- | ---- |
| [Umbra AutoRetainer](https://github.com/Qmeko/Umbra.AutoRetainer) | ツールバーに AutoRetainer のリテイナー／潜水艦の状態を出します（`R7\|20　M0\|4`）。クリックで `/ays` を開きます。 |

### Umbra AutoRetainer の入れ方

1. [Umbra](https://github.com/una-xiv/umbra) と [AutoRetainer](https://github.com/PunishXIV/AutoRetainer) を入れる
2. プロジェクトをビルドするか、`Umbra.AutoRetainer.dll` を用意する
3. Umbra の設定で **Custom Plugins** を有効にし、DLL を追加する
4. ツールバーに **AutoRetainer** ウィジェットを足す

## 連絡先

GitHub: [Qmeko](https://github.com/Qmeko)

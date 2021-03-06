# gitkraken-i18n
Unofficial GitKraken i18n project

## Contents
- [Japanese](README-ja.md)

## Change Language

**Please do this at your own risk! Please see [Known issues](https://github.com/megos/gitkraken-i18n/issues?q=is%3Aissue+is%3Aopen+label%3A%22known+issue%22).**

1. Replace project dir `strings.json` to GitKraken's `strings.json`.
   - Windows: `%LOCALAPPDATA%\gitkraken\app-x.x.x\resources\app.asar.unpacked\src\strings.json` (x.x.x is version)
   - Mac: `/Applications/GitKraken.app/Contents/Resources/app.asar.unpacked/src/strings.json`
1. Restart GitKraken.
1. Open the preferences.  
![Preferences Menu Button](./images/options_button.png)
1. Go to "UI Customization" and select the language.  
![UI Customization preferences](./images/ui_customization.png)

## Translate

1. Copy `strings.json` to `{locale}/strings.json`. (`{locale}` is the locale to translate)
1. Translate `{locale}/strings.json`.
1. Check translate [Change Language](#Change%20Language) for reference.

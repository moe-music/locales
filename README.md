# locales of MoE bot

<!-- https://discord.gg/2kmntjCscn -->
<!-- https://github.com/moe-music/locales -->

[![Discord](https://img.shields.io/discord/871329074046435338?color=7289da&logo=discord&logoColor=white)](https://discord.gg/2kmntjCscn)
[![Issues](https://img.shields.io/github/issues/moe-music/locales)](
    https://github.com/moe-music/locales/issues
)
[![Pull Requests](https://img.shields.io/github/issues-pr/moe-music/locales)](https://github.com/moe-music/locales/pulls)
[![License](https://img.shields.io/github/license/moe-music/locales)](
    https://github.com/moe-music/locales/blob/main/LICENSE
)
### This directory contains all the locales that are available for the bot

# available locales

| Locale | Flag | Language | Translated By | Status | Progress |
| --- | --- | --- | --- | --- | --- |
| `id` | 🇮🇩 | Indonesian |  | ✅ | 80%
| `en-US` | 🇺🇸 | English (US) | | ✅ | 100%
| `en-GB` | 🇬🇧 | English (GB) |  | ✅ | 100%
| `bg` | 🇧🇬 | Bulgarian |  | ✅ | 80%
| `zh-CN` | 🇨🇳 | Chinese (Simplified) |  | ✅ | 80%
| `zh-TW` | 🇹🇼 | Chinese (Traditional) |  | ✅ | 80%
| `hr` | 🇭🇷 | Croatian |  | ✅ | 80%
| `cs` | 🇨🇿 | Czech |  | ✅ | 80%
| `da` | 🇩🇰 | Danish |  | ✅ | 80%
| `nl` | 🇳🇱 | Dutch |  | ✅ | 80%
| `fi` | 🇫🇮 | Finnish |  | ✅ | 80%
| `fr` | 🇫🇷 | French |  | ✅ | 80%
| `de` | 🇩🇪 | German |  | ✅ | 80%
| `el` | 🇬🇷 | Greek |  | ✅ | 80%
| `hi` | 🇮🇳 | Hindi |  | ✅ | 80%
| `hu` | 🇭🇺 | Hungarian |  | ✅ | 80%
| `it` | 🇮🇹 | Italian |  | ✅ | 80%
| `ja` | 🇯🇵 | Japanese |  | ✅ | 80%
| `ko` | 🇰🇷 | Korean |  | ✅ | 80%
| `lt` | 🇱🇹 | Lithuanian |  | ✅ | 80%
| `no` | 🇳🇴 | Norwegian |  | ✅ | 80%
| `pl` | 🇵🇱 | Polish |  | ✅ | 80%
| `pt-BR` | 🇧🇷 | Portuguese (Brazil) |  | ✅ | 80%
| `ro` | 🇷🇴 | Romanian |  | ✅ | 80%
| `ru` | 🇷🇺 | Russian |  | ✅ | 80%
| `es-ES` | 🇪🇸 | Spanish (Spain) |  | ✅ | 80%
| `sv-SE` | 🇸🇪 | Swedish |  | ✅ | 80%
| `th` | 🇹🇭 | Thai |  | ✅ | 80%
| `tr` | 🇹🇷 | Turkish |  | ✅ | 80%
| `uk` | 🇺🇦 | Ukrainian |  | ✅ | 80%
| `vi` | 🇻🇳 | Vietnamese | [trương duy khải](https://discord.com/users/871329074046435338) | ✅ | 80%

## how to add a new locale

1. Create a new file in the `locales` directory with the name of the locale (e.g. `English (US)` would be `EnglishUS.json`).
2. Copy the contents of `EnglishUS.json` into the new file.
3. Translate the values of the strings into the new language.

<div class="warning" style="background-color: #fff3cd; color: #856404; padding: 10px; border: 1px solid #ffeeba; border-radius: 4px;">
    <strong>Note:</strong> Do not change the keys of the strings. Only translate the values.
</div>

e.g. `"hello": "Hello"` should be `"hello": "Hola"`.
Do not change `"hello"` to `"hola"`.
Also, do not change the keys of the strings. Only change the values.
e.g. `"hello": "{{{object}}} Hello"` should be `"hello": "{{{object}}} Hola"`.
Do not change `{{{object}}}` this object.

 <div class="warning" style="background-color: #fff3cd; color: #856404; padding: 10px; border: 1px solid #ffeeba; border-radius: 4px;">
    <strong>Note:</strong> If you are using a text editor that does not support Unicode characters, you can use the <a href="https://en.wikipedia.org/wiki/Code_point">Unicode code point</a> instead. For example, <code>🇺🇸</code> would be <code>\uD83C\uDDFA\uD83C\uDDF8</code>.
</div>

## how to edit

1. Fork this repository.
2. Edit the file. (Use [Visual Studio Code](https://code.visualstudio.com/) or [Notepad++](https://notepad-plus-plus.org/) for better editing experience.)
3. Create a pull request.

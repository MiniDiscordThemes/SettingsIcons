[screenshot]:       https://github.com/MiniDiscordThemes/SettingsIcons/assets/8350274/7d68e35b-17c0-40e5-9605-84a4ddbba191

[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length
[discord]:          https://discord.gg/uy8nKQVatp

[Vencord]:          https://github.com/Vendicated/Vencord

[shield-vc-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/SettingsIcons/SettingsIcons.theme.css?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/SettingsIcons?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/SettingsIcons
[issues]:           https://github.com/MiniDiscordThemes/SettingsIcons/issues
[license]:          https://github.com/MiniDiscordThemes/SettingsIcons/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/SettingsIcons/blob/main/SettingsIcons.theme.css

[release-vc-gh]:    https://github.com/MiniDiscordThemes/SettingsIcons/releases/latest/download/SettingsIcons.theme.css "Get latest release"

# SettingsIcons Discord Theme
[![Vencord GitHub downloads][shield-vc-dl]][release-vc-gh]
[![Total repository size][shield-repo-size]][github]

***Adds icons to Discord settings, for use with Vencord plugin ThemeAttributes.***

![Screenshot of SettingsIcons applied to Vencord settings][screenshot]

## Installation
<details><summary>Click to expand</summary>

⚠️ This theme is designed for use with [Vencord][Vencord]; other client mods are not supported.

Enable the `ThemeAttributes` plugin in `Settings` > `Vencord` > `Plugins`.
### Local
1. Download `SettingsIcons.theme.css`:
    - [GitHub][release-vc-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/SettingsIcons/SettingsIcons.theme.css`
</details>

## Customisation

| Variable name     | Description               | Valid values              | Default value |
| ----------------- | ------------------------- | ------------------------- | ------------- |
| `--settingsicons` | Enable SettingsIcons      | `show` or `hide`          | `show`        |
| `--si-size`       | Icon size                 | Any [length][css-length]. | `18px`        |
| `--si-gap`        | Gap between icon and text | Any [length][css-length]. | `14px`        |

<details><summary>Click to expand</summary>

#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `SettingsIcons.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`SettingsIcons.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
- Copyright (c) 2021-2023 Mirco Wittrien (original)
- Copyright (c) 2023-2024 MiniDiscordThemes (modifications in this repository)

This theme is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This theme is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Affero General Public License][license] for more details.

## Credits
[si]:               https://github.com/mwittrien/BetterDiscordAddons/blob/master/Themes/_res/SettingsIcons.css
[si-author]:        https://github.com/mwittrien

[ionicons]:         https://github.com/ionic-team/ionicons
[ionicons-author]:  https://github.com/ionic-team

- [SettingsIcons][si] by [Mirco Wittrien (DevilBro)][si-author] - GPL-2.0 license
- [Ionicons][ionicons] by [Ionic][ionicons-author] - MIT license

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
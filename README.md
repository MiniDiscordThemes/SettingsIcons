[screenshot]:       https://cdn.discordapp.com/attachments/1142305515439923260/1151000047396339792/settingsicons.png

[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length
[discord]:          https://discord.gg/uy8nKQVatp

[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/SettingsIcons/SettingsIcons.theme.css?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/SettingsIcons?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/SettingsIcons
[issues]:           https://github.com/MiniDiscordThemes/SettingsIcons/issues
[license]:          https://github.com/MiniDiscordThemes/SettingsIcons/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/SettingsIcons/blob/main/SettingsIcons.theme.css

[si]:               https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/SettingsIcons
[si-author]:        https://github.com/mwittrien
[si-license]:       https://github.com/mwittrien/BetterDiscordAddons/blob/master/LICENSE

[release-bd-gh]:    https://github.com/MiniDiscordThemes/SettingsIcons/releases/latest/download/SettingsIcons.theme.css "Get latest release"

# SettingsIcons Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Total repository size][shield-repo-size]][github]

***Adds icons to Discord settings, for use with Vencord plugin ThemeAttributes.***

![Screenshot of SettingsIcons applied to Vencord settings][screenshot]

## Installation

### [Vencord][Vencord]
Enable the `ThemeAttributes` plugin in `Settings` > `Vencord` > `Plugins`.
#### Local
1. Download `SettingsIcons.theme.css`:
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/SettingsIcons/SettingsIcons.theme.css`

## Customisation

| Description                    | Variable name    | Valid values              | Default value |
| ------------------------------ | ---------------- | ------------------------- | ------------- |
| Enable SettingsIcon            | `--settingsicon` | `1` (on) or `0` (off)     | `1`           |
| Icon size                      | `--si-size`      | Any [length][css-length]. | `18px`        |
| Distance between icon and text | `--si-gap`       | Any [length][css-length]. | `14px`        |

### Vencord
#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `SettingsIcons.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`SettingsIcons.theme.css`][.theme.css].
3. Edit the variable values.

## License
[GNU General Public License v2.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

### Includes
- [SettingsIcons][si] by [DevilBro][si-author] - [GPL-2.0][si-license]

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].

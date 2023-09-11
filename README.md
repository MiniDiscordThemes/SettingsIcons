[screenshot]:       https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/SettingsIcons1.png
[light]:            https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/SettingsIcons1.png
[dark]:             https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/SettingsIcons1.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/SettingsIcons/SettingsIcons.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/SettingsIcons/net.saltssaumure.SettingsIcons.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/SettingsIcons?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/SettingsIcons
[issues]:           https://github.com/MiniDiscordThemes/SettingsIcons/issues
[license]:          https://github.com/MiniDiscordThemes/SettingsIcons/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/SettingsIcons/blob/main/SettingsIcons.theme.css

[er]:               https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/EmojiReplace
[er-author]:        https://github.com/mwittrien
[er-license]:       https://github.com/mwittrien/BetterDiscordAddons/blob/master/LICENSE

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.SettingsIcons "Replugged store page"
[release-bd-gh]:    https://github.com/MiniDiscordThemes/SettingsIcons/releases/latest/download/SettingsIcons.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/MiniDiscordThemes/SettingsIcons/releases/latest/download/net.saltssaumure.SettingsIcons.asar "Get latest release"

# SettingsIcons Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A SettingsIcons Discord theme for multiple client mod support.***

![Screenshot of SettingsIcons applied to Discord][screenshot]

| Light mode                                                          | Dark mode                                                         |
| ------------------------------------------------------------------- | ----------------------------------------------------------------- |
| ![Screenshot of SettingsIcons light mode applied to Discord][light] | ![Screenshot of SettingsIcons dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `SettingsIcons.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Replugged][Replugged]
#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.SettingsIcons.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `SettingsIcons.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/SettingsIcons/SettingsIcons.theme.css`

## Customisation

| Description                    | Variable name     | Valid values                            | Default value |
| ------------------------------ | ----------------- | --------------------------------------- | ------------- |
| Background colour              | `--temp-bg-color` | Any [CSS-recognised][css-color] colour. | #000          |
| &#9936; Moving scanline on/off | `--temp-scanline` | `block` (on) or `none` (off).           | `block`       |
| &#9888; Screen flicker on/off  | `--temp-flicker`  | `flicker` (on) or `none` (off).         | `none`        |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-20 of [`SettingsIcons.theme.css`][.theme.css].
4. Edit the variable values and save.

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
- [EmojiReplace][er] by [DevilBro][er-author] - [GPL-2.0][er-license]

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
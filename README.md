# Dark Discord
An actual dark theme for Discord

Great for those who thinks the normal discord dark mode is literally just light mode

## Requirements

[BetterDiscord](https://github.com/BetterDiscord/BetterDiscord) is required to be installed

[Betterdiscordctl](https://github.com/bb010g/betterdiscordctl) might be a handy tool to install BetterDiscord on Linux

### BetterDiscord Installers

- Windows
Grab the `exe` file from [here](https://github.com/BetterDiscord/Installer/releases/latest/download/BetterDiscord-Windows.exe).

- macOS/OS X
Grab the `zip` file from [here](https://github.com/BetterDiscord/Installer/releases/latest/download/BetterDiscord-Mac.zip).

- Linux
Grab the `AppImage` file from [here](https://github.com/BetterDiscord/Installer/releases/latest/download/BetterDiscord-Linux.AppImage), or use [Betterdiscordctl](https://github.com/bb010g/betterdiscordctl).

Sometimes BetterDiscord can get disabled after a discord update, in that case just install it again, it should keep all the configs

## Installation Instructions

### Install as a theme

- Go to the `Themes` tab in Discord's settings (BetterDiscord section)
- Click on the `Open Theme Folder` button
- Drag `dark-discord.theme.css` into the folder
  - You can also use `dark-discord.theme.min.css`
- Go back to the `Themes` tab in Discord's settings, enable the theme with the switch

### Install as a custom CSS

The custom CSS option can be useful if your install of betterdiscord is bugged or not supported fully

To use this option,

- Go to the `Custom CSS` tab in Discord's settings
- Copy the content in `dark-discord.scss` ([here](https://raw.githubusercontent.com/Shuzhengz/dark-discord/main/dark-discord.scss))
- Paste in the textbox
- Click on the save button, then the update button to apply


## Customize

You can customize this theme by changing the color hex codes in the file

(Be careful, there's a lot of them)

You can also customize any other component by opening discord in your browser, and see the components using the inspect tool.

Simply copy the container (i.e. `.container-ZMc96U`) and then set the properties you want using standard CSS.

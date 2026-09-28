# ChangeIcons

Adds icons to your account: Sherpa, Emissary, Developer, Unheard or Edge of Darkness.

Server mod for SPT (SP-Tushonka) 4.1.

## Features

Message **SPT** in your friends list:
- `spt membercategory` - what you have now
- `spt membercategory list` - what you can add
- `spt membercategory 1026` or `spt membercategory unheard+uniqueid` - set your icons
- `spt membercategory default` - remove them

Fully restart the game after a change. Choose which icon is shown in the profile settings.

Trader, Group, System and other service flags can't be set, they break the profile.

## Installation

Unpack the [release archive](https://github.com/Evgencheg/Tarkov-Change-Icons/releases/latest) into your SPT game folder.

You should get `SPT_Runtime/user/mods/ChangeIcons/ChangeIcons.dll`.

## Uninstallation

Delete `SPT_Runtime/user/mods/ChangeIcons`.

Your icons stay on the account. To remove them, send `spt membercategory default` before deleting the mod.

## Building

```
dotnet build src/ChangeIcons/ChangeIcons.csproj -c Release
```

Needs the .NET 10 SDK.

## Credits

- Evgencheg - author
- Made with help from an AI coding assistant

[MIT](LICENSE)

# ChangeIcons

Server mod for SPT (SP-Tushonka) 4.1 that lets you add icons to your account: Sherpa, Emissary, Developer, Unheard or Edge of Darkness.

## Install

Unpack the [release zip](https://github.com/Evgencheg/Tarkov-Change-Icons/releases/latest) into your SPT game folder.
You should get `SPT_Runtime/user/mods/ChangeIcons/ChangeIcons.dll`.

## Use

Message **SPT** in your friends list:

- `spt membercategory` — what you have now
- `spt membercategory list` — what you can add
- `spt membercategory 1026` or `spt membercategory unheard+uniqueid` — set your icons
- `spt membercategory default` — remove them

Re-login after a change. Choose which icon is shown in the profile settings.

Trader, Group, System and other service flags can't be set, they break the profile.

## Remove

Send `spt membercategory 0`, then delete `SPT_Runtime/user/mods/ChangeIcons`.

## Build

```
dotnet build src/ChangeIcons/ChangeIcons.csproj -c Release
```

Needs the .NET 10 SDK. Made with help from an AI coding assistant. [MIT](LICENSE)

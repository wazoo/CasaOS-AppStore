# CasaOS AppStore

This repository is an app store for [CasaOS](https://www.casaos.io) and it has a bunch of apps that I use sometimes with customized settings to make them the same between the sources. Most of them probably work.

# Common Settings

## Paths

- /opt/appdata - Application Data Storage
- /opt/userfiles - User file storage (NextCloud data etc)
- /opt/media - media storage

## Port List

I have used the following port numbers for these applications and tried to stay with the default where there weren't any collisions.

|Port|App|Default|
|---|---|---|---|
|80|nginxproxymanager|yes|
|81|nginxproxymanager|yes|
|443|nginxproxymanager|yes|
|5432|Postgres|yes|
|32400|Plex|yes|

# Sources

## Container Images

When possible I use a project's official image, if that is not available then a [linuxserver.io](https://fleet.linuxserver.io/) is used.

## Icons

I used Icons from these places:

- [walkxcode/dashboard-icons](https://github.com/walkxcode/dashboard-icons)
- [iceWhaleTech/CasaOS-AppStore](https://github.com/iceWhaleTech/CasaOS-AppStore)

Lots of code was borrowed and customized from these places: 

- [Official Store](https://github.com/iceWhaleTech/CasaOS-AppStore)
- [Cp0204/CasaOS-AppStore-Play](https://github.com/Cp0204/CasaOS-AppStore-Play)
- [WisdomSky/CasaOS-LinuxServer-AppStore](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore)
- [WisdomSky/CasaOS-Coolstore](https://github.com/WisdomSky/CasaOS-Coolstore)
- [WisdomSky/CasaOS-AppStore-Edge](https://github.com/WisdomSky/CasaOS-AppStore-Edge)
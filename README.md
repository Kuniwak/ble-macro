Bluetooth Low Energy Macros
===========================

Files
-----

The URL is like `https://ble-macro.kuniwak.com/<path>`. Available paths are following:


| Path                                                            | Description                                     |
|:----------------------------------------------------------------|:------------------------------------------------|
| [iphone/battery-level.xml](./public/iphone/battery-level.xml)   | Read battery level                              |
| [switchbot/push.xml](./public/switchbot/push.xml)               | Push SwitchBot (confirmed at v6.3)              |
| [hue/make-discoverable.xml](./public/hue/make-discoverable.xml) | Make Philips Hue bonding available              |
| [hue/turn-off.xml](./public/hue/turn-off.xml)                   | Turn off Philips Hue                            |
| [hue/all-green.xml](./public/hue/all-green.xml)                 | Turn on Philips Hue with green                  | 
| [hue/autumn-gold.xml](./public/hue/autumn-gold.xml)             | Turn on Philips Hue with "autumn gold" scene    |                  | 
| [hue/daylight-white.xml](./public/hue/daylight-white.xml)       | Turn on Philips Hue with "daylight white" scene |
| [hue/relax.xml](./public/hue/relax.xml)                         | Turn on Philips Hue with "relax" scene          |


References
----------

* Macro Specifications
    * [Macros/README.md - NordicSemiconductor/Android-nRF-Connect/](https://github.com/NordicSemiconductor/Android-nRF-Connect/blob/main/documentation/Macros/README.md)
* Switchbot
    * [devicetypes/bot.md - OpenWonderLabs/SwitchBotAPI-BLE](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE/blob/latest/devicetypes/bot.md)
* Philips Hue
    * [nRF Connect のマクロ機能で Philips Hue をLチカする - Nature Engineering Blog](https://engineering.nature.global/entry/nrf-connect-macro)
    * [hue-ble-ctl.py - Mic92/hue-ble-ctl](https://github.com/Mic92/hue-ble-ctl)
    * [Philips Hue BLE Services and Characteristics (WIP) - shinyquagsire23](https://gist.github.com/shinyquagsire23/f7907fdf6b470200702e75a30135caf3)

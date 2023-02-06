# CONFIGURE GUI


## Bartender

general:
```
+ Launch Bartender at login
+ Use Bartender Bar to show hidden items + Only on screen with Notch
```

### menu bar layout - narrow screen
#### shown
- Lungo
- iStat Menus / CPU
- iStat Menus / MEM
- iStat Menus / SENSORS
- iStat Menus / BATTERY
- Audio (system)
#### hidden
- **everything else**
#### always hidden
- Scrip tMenu (system)
- Battery (system)
- DYMO
- Bitwarden
- Keybase

### menu bar layout - wide screen
#### shown
- **spacer**
- iStat Menus / CPU
- iStat Menus / MEM
- iStat Menus / DISKS
- iStat Menus / NET
- iStat Menus / SENSORS
- **spacer**
- Lungo
- Focus Mode (system)
- Flow
- **spacer**
- Multipass
- Docker Desktop
- **spacer**
- Mosaic
- Pixel Snap
- CleanShotX
- LanguageTool Desktop
- **spacer**
- MacUpdater
- CleanMyMacX
- AltServer
- KopiaUI
- TimeMachine (system)
- **spacer**
- VPN (system)
- WiFi (system)
- Audio (system)
- iStat Menus / CALENDAR
- *Control Center (system)*
- *Clock (system) - HH:MM:SS*
#### hidden
- User Switcher (system)
- SetApp
#### always hidden
- Scrip tMenu (system)

## iStatMenus

Import `~/dsenv/mac/iStatMenusSettings.ismp` XOR `~/dsenv/mac/iStatMenusSettings_MacBook.ismp``

## Mosaic

Import `~/dsenv/mac/Mosaic.mosaicprefs`

## CleanShotX

general:
```
+ start at login
+ play sounds
+ menu bar: show icon

export location:  ~/Pictures/screenshots
+ desktop icons: hide while capturing

after capture:
  show quick capture overlay: screenshot, recording
  copy file to clipboard: screenshot, recording
  save: screenshot, recording
  upload: --
  open annotate tool: --
  pin to the screen: --
  open video editor: --
```

wallpaper:
```
use desktop wallpaper

padding: min
window shadow: none
```

quick access:
```
position: left
overlay size: max

+ auto-close
  + save&close
  interval: 5 minutes
+ drag & drop: close after draggin
save button: save to export location
```

screenshot:
```
format: png
- retina scale
- frame

self-timer: 5 seconds
+ freeze screen
crosshair mode: always enabled
  + show magnifier
```

advanced:
```
file-name: `Screenshot ,%y,-,%m,-,%d, at ,%H,.,%M,.,%S`
- ask for name
- `@2x`

copy to clipboard: File & Image

+ pinned: rounded corners
+ pinned: shadow
+ pinned: border

keep history: 1 week

+ all-in-one: remember
```

## BetterDisplay

licence string

### Dummy

single 16:9

### Main

- stream - cropping area: `50.00%` x `100.00%`, relative: X `25.00%` Y `0.00%`
- stream -> to "Dummy"


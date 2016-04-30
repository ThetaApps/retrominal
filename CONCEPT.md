UNIX Terminal library for multiple retro console emulation.

Loosely based off of cores from [RetroArch](https://github.com/libretro/RetroArch) and [OpenEmu](https://github.com/OpenEmu/OpenEmu).

Built with libraries from [libtermboy](https://github.com/dobyrch/libtermboy).



# Commands

`emu4unix help`



## Nintendo Entertainment System

`nes4unix help`

### Change Settings

`nes4unix set -h`

`nes4unix set SETTING VALUE`

| Setting    | Description    | Values    |
|-----------:|:--------------:|:----------|
| btn-a      | A Button       | 0-9, a-z, ←↑↓→, ⌃⌘⌥⇧↩︎⌫
| btn-b      | B Button       | 
| btn-start  | Start Button   | 
| btn-select | Select Button  | 
| dpad-up    | D-Pad Up       | 
| dpad-down  | D-Pad Down     | 
| dpad-left  | D-Pad Left     | 
| dpad-right | D-Pad Right    | 



### Run Roms (NES)

`nes4unix run /path/to/rom`

`nes4unix run -t "Title"`

`nes4unix run -n "Number"`



### Manage Library (NES)

`nes4unix add -t "Title" -n "Number" /path/to/rom`

`nes4unix edit -t "Title"`

`nes4unix edit -n "Number"`

`nes4unix add -d /path/to/roms/folder`



## Super Nintendo Entertainment System

`snes4unix help`

`snes4unix run /path/to/rom`



## Game Boy

`gb4unix help`

`gb4unix run /path/to/rom`



## Game Boy Color

`gbc4unix help`

`gbc4unix run /path/to/rom`



## Game Boy Advance

`gba4unix help`

`gba4unix run /path/to/rom`

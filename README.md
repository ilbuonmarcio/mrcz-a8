# mrcz's Anet A8 custom build config
#### Updated to Marlin 2.0.5.3

Requirements:

- A working Anet A8 printer to begin with
- Internet connection
- A working computer (tested on Windows 10 2004 build)

Resources:

- Download Marlin 2.0.5.3 source code [here](https://github.com/MarlinFirmware/Marlin/releases)
- Download Marlin 2.0.5.3 board configurations [here](https://github.com/MarlinFirmware/Configurations/releases)
- Download Anet A8 board definition for Marlin from master branch [here](https://github.com/SkyNet3D/anet-board)
- Download Arduino [here](https://www.arduino.cc/en/main/software)

- - -

## Steps

- Install Arduino IDE
- Copy Anet A8's board definition `adr` you can find under `anet-board-repo-folder/hardware` to the `Arduino/hardware` system application folder
  (on Windows should be `C:\Program Files (x86)\Arduino\hardware`)
- Run Arduino IDE and go to Tools -> Board and set Anet V1.0 as your board definition for code compilation

# Myliobatis
FDM 3D printer motherbords based on STM32F407VG/STM32F103RE
This projects contains design of motherbords for FDM 3d printers. Where 3 variants of its:
1) <b>Mobula Ray</b>. This motherbords based on STM32F407VG microcontroller. Motherbords contains:
  - 6 stepper motors drivers TMC2224 (same as TMC2208) controlled by UART. Microsteps, stepper are current controlled by firmware. 
  - 6 PWM output - Heatbed, 3 x heaters, 2 controlled fans
  - 4 temperature inputs
  - 6 inputs for XMIN, XMAX, YMIN, YMAX, ZMIN, ZMAX
  - 3 inputs for filament detectors
  - BlTouch connector
  - onboard WiFi
  - connector for external GSM module
  - connectors SPI/I2C/UART interfaces
  - EXT1/EXT2 connectrs for displays/external SD card
  - SWD connector
  - USB-B
  - micro SD
  - switch after end of print output
  - connectors for 9 programmable pins 
  - board size 150 x 120 mm
  <br>Project page on easyeda.com https://easyeda.com/mmaygli/mid-bro
  2) <b>Manta Ray</b>. This motherbords based on STM32F407VG microcontroller. Has two variants. Variant A has common power suplay for heaters/fans and drivers. 
  Variant B has separate connectors for heaters and motor drivers. Motherbords contains:
  - Connectrs for 6 stepper motors compatible with A4988 (A4988, DRV8825, TMC2100, TMC2130, TMC2208, etc). 
  - 6 PWM output - Heatbed, 3 x heaters, 2 controlled fans
  - 4 temperature inputs
  - 6 inputs for XMIN, XMAX, YMIN, YMAX, ZMIN, ZMAX
  - 3 inputs for filament detectors
  - BlTouch connector
  - onboard WiFi
  - connector for external GSM module
  - connectors SPI/I2C/UART interfaces
  - EXT1/EXT2 connectrs for displays/external SD card
  - SWD connector
  - USB-B
  - micro SD
  - switch after end of print output
  - connectors for 13 programmable pins
  - board size 150 x 120 mm
  <br>Project pages on easyeda.com: https://easyeda.com/mmaygli/test3d, https://easyeda.com/mmaygli/bigbro-external-drivers-common-power
  1) <b>Sting Ray</b>. This motherbords based on STM32F103RE microcontroller.  
  Variant B has separate connectors for heaters and motor drivers. Motherbords contains:
  - Connectrs for 5 stepper motors compatible with A4988 (A4988, DRV8825, TMC2100, TMC2130, TMC2208, etc). 
  - 4 PWM output - Heatbed, 2 x heaters, 1 controlled fans
  - 3 temperature inputs
  - 6 inputs for XMIN, XMAX, YMIN, YMAX, ZMIN, ZMAX
  - filament detector input
  - BlTouch connector (shared with ZMAX, YMAX)
  - connectors I2C/UART interfaces
  - EXT1/EXT2 connectrs for displays/external SD card
  - SWD connector
  - USB-B
  - micro SD
  - board size 112 x 100 mm
<br>Project page on easyeda.com https://easyeda.com/mmaygli/stm32f103-3d-printer-board
<br> Status on 9 of Dec 2018: <b>Boards just desined. Its have never be assembled and tested</b>
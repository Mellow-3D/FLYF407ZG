# FLYF407ZG
If you have any usage problems, please join https://discord.gg/hccjyvv
Come to consult me


## What firmware does FLYF407 already support?
Reprapfirmware,Marlin2.0,Klipper

# How to configure and use this motherboard in Marlin?
1.modify platformio.ini file
  default_envs = FLYF407ZG
2.modify Configuration.h  file
  #define MOTHERBOARD BOARD_FLYF407ZG
  #define SERIAL_PORT   -1
  #define SERIAL_PORT_2  1
  

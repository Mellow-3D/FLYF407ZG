# FLYF407ZG

The Fly-F407ZG can be purchased here https://s.click.aliexpress.com/e/_DlS6n9R

This link is affiliated URL. If you purchase via link above it will give tiny cent of commission to the community organizers. (We are not Mellow employees, just 3D printer enthusiasts) This will not hurt your wallet and at the same time help us to maintain the GitHub better.

If you have any usage problems, please join https://discord.gg/hccjyvv
Come to consult me


## What firmware does FLYF407 already support?
Reprapfirmware,Marlin2.0,Klipper

# How to configure and use this motherboard in Reprap?

1.You can check the manual in this github, reprapfirmware folder

2.You can visithttps://github.com/gloomyandy/RepRapFirmware/wiki/Fly-407ZG-Wifi

# How to configure and use this motherboard in Marlin?
1.modify platformio.ini file

  default_envs = FLYF407ZG
  
2.modify Configuration.h  file

  #define MOTHERBOARD BOARD_FLYF407ZG
  
  #define SERIAL_PORT   -1
  
  #define SERIAL_PORT_2  1
  

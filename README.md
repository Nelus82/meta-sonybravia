# meta-sonybravia

## General
This driver is to control your Sony Bravia from your Neeo with help of meta2 (https://github.com/jac459/meta). It should work for most Sony Bravia TV's, but button commands may differ between different devices. I made it as simple as possible for my needs. The driver uses the REST API and IRCC-IP of Sony Bravia (https://pro-bravia.sony.net/develop/integrate/ip-control/index.html). If you miss something do not hesitate to ask or help.

## Requirements
- Neeo
- working installation of meta2 (https://github.com/jac459/meta)
- Sony Bravia with fixed ip
- Sony Bravia with PSK 1111 


## Configure Sony Bravia PSK
[Home] Settings > Network > IP Control > Authentication
  - Change Authentication to Pre-Shared Key

[Home] Settings > Network > IP Control > Pre-Shared Key
  - Enter the Pre-Shared Key

If you cannot find the options in your Settings menu. You may need to enable Pro settings mode.


## Installation instructions
- Add Device on Neeo
- Search driver (Bravia)
- Device will be discovered. Select the propper device by naming.
- Select a room which the device should be added.
- Setup the device acording your needs

I want to thank Jac459 and MarkusM for helping me and for creating this fantastic piece of software that brings our Neeo to life (as it was intended).

Telegram Group: https://t.me/joinchat/NocMDU9RCVP9hSCJxPsCEg

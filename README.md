# mcstatus
A minecraft query staus checker using API from mcstatus.io
# Installation
You only need to install `jq` and `curl` on your Linux distributions (`getopt` might included cuz some machine like Mac OS don't have it installed by default idk)
# Usage
```
$ mcstatus
Usage: mcstatus [-abhvV] <address>

  -a, --no-address
    Don't show the IP Address.
  -h, --help
    Display this help.
  -m, --show-mods
    Display list of mods.
  -p, --hide-plugins
    Hide plugins list.
  -v, --hide-versions
    Don't show server version.
  -V, --verbose
    Turn on verbose mode (debug mode).

More information about this command or filing a bugs, visit this repository: <https://github.com/crischutu07/mcstatus>
```
# Examples
Fetch `demo.mcstatus.io` with mods and hide plugins
```
$ mcstatus -m --hide-plugins demo.mcstatus.io
mcstatus -m --hide-plugins demo.mcstatus.io
(✓) Address: demo.mcstatus.io (144.172.70.183)
Version: 1.20.1
Mods (3)
├── applied-energistics-2 (11.7.2)
├── accelerated-decay (0.1.3)
└── iron-chests (13.2.11)
===
    ;;; >>> Minecraft Server Status <<< ;;;
             https://mcstatus.io/
===
Players (71/100)
├── www_makin_cc
├── Planeta_Play
├── Fran_CM
├── spidunno
└── PassTheMayo
```
# License
This repository is licensed under MIT License
Read it [here](https://github.com/crischutu07/mcstatus/blob/main/LICENSE)

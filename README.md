# Daemonbite-Controller-Hub

![daemonbite-controller-hub](https://user-images.githubusercontent.com/83313810/116638859-3572aa00-a935-11eb-8ef9-114f12c992d6.png)

This is an add-on board for the MiSTer FPGA project to provide original hardware inputs for SNES, NES and Genesis controllers using Daemonbite adapters (see https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB). The current version serves only as a mount for the Daemonbites and controller ports.

# Parts needed (v0.1):

- 2x Pro Micro ATmega32U4 (micro USB): https://www.aliexpress.com/item/1005001335338291.html
- 2x Micro USB cable: https://www.aliexpress.com/item/4000378492248.html
- 2x DB9 male port: https://www.aliexpress.com/item/33047048440.html
- 2x SNES port (90 degree): https://www.aliexpress.com/item/32838396935.html
- 2x NES port (90 degree): https://www.aliexpress.com/item/32875874969.html
- 4x M3 Male 6mm x M3 Female 20mm Standoff: https://www.aliexpress.com/item/32667773402.html

# Roadmap

- Integrate ATmega32U4 directly on board
- Integrate 7-port powered USB hub to board

# Issues

- Need to verify that 4 controllers (2x SNES and 2x NES) can be run through a single Pro Micro (see https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB/issues/3).

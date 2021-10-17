# Ubuntu Miner
- Ubuntu Server 20.04
- T-rex Miner (configured for 3x RTX 3070)
- Tested on AMD Ryzen 5 1600

## Setup
Enable overclocking:
`nvidia-xconfig -a --enable-all-gpus`
`nvidia-xconfig -a --cool-bits=28 --allow-empty-initial-configuration`

Start miner with `./start`

## GRUB
`GRUB_CMDLINE_LINUX_DEFAULT="text nouveau.modeset=0"`

## BIOS
- PCIe Link Speed: GEN 2

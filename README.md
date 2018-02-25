# Linux

## Overview
Kernel: 4.15.3

|   | HP Thunderbolt 3 Dock | Thinkpad Thunderbolt 3 Dock |
|---|---|---|
|Power delivery| :exclamation: Works but unstable (screen flickering, etc.) | :white_check_mark: |
|External dual screen| :white_check_mark: | :white_check_mark: |
|USB| :white_check_mark: | |
|Ethernet | :x: | :x: |
|Audio | | |


## HP Thunderbolt 3 Dock

### Ethernet
Ethernet controller: Broadcom Limited NetXtreme BCM57762 Gigabit Ethernet PCIe (rev 01)
Kernel modules: tg3

```
tg3.c:v3.137 (May 11, 2014)
tg3 0000:07:00.0: phy probe failed, err -19
tg3 0000:07:00.0: Problem fetching invariants of chip, aborting
```

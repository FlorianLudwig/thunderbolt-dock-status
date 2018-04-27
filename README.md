# Linux

## Overview
Kernel: 4.15.3

|   | HP Thunderbolt 3 Dock | Thinkpad Thunderbolt 3 Dock |
|---|---|---|
|Power delivery| :exclamation: Works but unstable (screen flickering, etc.) | :white_check_mark: |
|External dual screen| :white_check_mark: | :white_check_mark: |
|USB| :white_check_mark: | |
|Ethernet | :x: Unstable | :x: |
|Audio | | |


## HP Thunderbolt 3 Dock

### Ethernet
Ethernet controller: Broadcom Limited NetXtreme BCM57762 Gigabit Ethernet PCIe (rev 01)
Kernel modules: tg3

```
tg3.c:v3.137 (May 11, 2014)
tg3 0000:07:00.0 eth0: Tigon3 [partno(BCM957762) rev 57766001] (PCI Express) MAC address 30:e1:71:90:74:a3
tg3 0000:07:00.0 eth0: attached PHY is 57765 (10/100/1000Base-T Ethernet) (WireSpeed[1], EEE[1])
tg3 0000:07:00.0 eth0: RXcsums[1] LinkChgREG[0] MIirq[0] ASF[0] TSOcap[1]
tg3 0000:07:00.0 eth0: dma_rwctrl[00000001] dma_mask[64-bit]
tg3 0000:07:00.0 enp7s0: renamed from eth0
tg3 0000:07:00.0 enp7s0: Link is up at 1000 Mbps, full duplex
tg3 0000:07:00.0 enp7s0: Flow control is off for TX and off for RX
tg3 0000:07:00.0 enp7s0: EEE is enabled

```

Might also end up with:
```
tg3.c:v3.137 (May 11, 2014)
tg3 0000:07:00.0: phy probe failed, err -19
tg3 0000:07:00.0: Problem fetching invariants of chip, aborting
```

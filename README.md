<!--
title: Broadcom brcm Supplemental Firmware & NVRAM
description: Board specific brcm firmware & NVRAM not found in linux-firmware repo
layout: Doc
-->
# Broadcom brcm Supplemental Firmware & NVRAM

This repository contains board specific firmware & NVRAM for Broadcom brcm devices. File names have been renamed to be board specific which aligns with how OpenBSD's bwfm driver loads them.

## Boards

### CuBox-i
<pre><code>
  Source Location:
    https://github.com/Freescale/meta-freescale-3rdparty/tree/master/recipes-bsp/broadcom-nvram-config/files/cubox-i

  Renamed to be board specific and set ccode=X2:
    brcmfmac4330-sdio.solidrun,cubox-i.txt
</code></pre>

### Pinebook Pro
<pre><code>
  Source Location:
    https://gitlab.manjaro.org/tsys/pinebook-firmware/-/tree/master/brcm

  Renamed to be board specific:
    brcmfmac43456-sdio.pine64,pinebook-pro.bin
    brcmfmac43456-sdio.pine64,pinebook-pro.txt
</code></pre>
### Rock960
<pre><code>
  Source Location:
    https://people.linaro.org/~manivannan.sadhasivam/rock960_wifi/

  Renamed to be board specific and set ccode=X2:
    brcmfmac4356-sdio.vamrs,rock960.bin
    brcmfmac4356-sdio.vamrs,rock960.txt

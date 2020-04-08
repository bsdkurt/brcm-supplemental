<!--
title: Broadcom brcm Supplemental Firmware
description: Board specific brcm firmware not found in linux-firmware repo
layout: Doc
-->
# Broadcom brcm Supplemental Firmware

This repository contains board specific firmware for Broadcom brcm devices. The firmware has been renamed to be board specific which aligns with how OpenBSD's bwfm driver loads them.

## Boards

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

  Renamed to be board specific:
    brcmfmac4356-sdio.vamrs,rock960.bin
    brcmfmac4356-sdio.vamrs,rock960.txt

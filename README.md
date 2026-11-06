# Boot File

## Overview
This repository contains the custom patched `boot.img` and related flashing files for the **Infinix-X6352-v3278** device.

## Device Information
* **Model:** Infinix X6352
* **Build / Version:** v3278
* **Target File:** `boot.img`

## Flashing Instructions
1. Unlock the bootloader of your Infinix device.
2. Boot into fastboot mode.
3. Flash the patched boot image using the following command:
   ```bash
   fastboot flash boot boot.img

# Infinix Hot 30 Magisk Modules

Backup of the Magisk modules installed on the Infinix Hot 30 (X6831, Magisk 26.3).

## Contents

- Magisk_Bootloop_Protector-v1.8.1.zip - HuskyDG BootloopSaver v1.8.1. Watches zygote; on a zygote crash loop it disables all other modules and reboots. Use basic mode (no boot patch). It recovers from module-caused bootloops; it does not prevent them.
- ThermalOff_Hot30.zip - Disables all thermal zones (late_start service). Kernel thermal throttling off. Manage heat yourself; use at your own risk.
- MaxPerf_Hot30.zip - Holds the Helio G88 at its factory-max clocks (performance governor, 1.8/2.0 GHz caps). This is max stock performance, not overclock - true overclock is impossible on the stock kernel.
- RedMagic11ProPlusSpoof_v2.zip - Spoofs Nubia Red Magic 11 Pro+ (NX809J, SM8850-AC, Adreno 840) so games unlock Red Magic graphics tiers (verified: PUBG Ultra Extreme on Smooth). No fingerprint spoof. Remove other spoof modules first, install only this one, reboot.

## Install

Install via the Magisk app, one module at a time, then reboot. Props and services need a reboot to take effect.

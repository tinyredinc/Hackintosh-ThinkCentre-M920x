# Hackintosh-ThinkCentre-M920x
Hackintosh, OpenCore EFI for Lenovo ThinkCentre M920x / P330 Tiny

## Hardware Specs

- Platform: Lenovo ThinkCentre M920x(P330 Tiny)
- CPU: Intel Core i5-8500 (Coffee Lake)
- iGPU：Intel UHD Graphics 630
- dGPU: AMD Radeon Pro WX 4100 (Polaris/Baffin)
- RAM:
- SSD:
- LAN:
- WLAN: Apple BCM94360CS2

## OpenCore EFI

### Drivers 
| Name | Version | URL |
|---|---|---|
| OpenRuntime.efi | 1.0.0 | https://github.com/acidanthera/OpenCorePkg/releases |
| ResetNvramEntry.efi | 1.0.0 | https://github.com/acidanthera/OpenCorePkg/releases |
| HfsPlus.efi | c2a9898 | https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi |

### Kexts
| Name | Version | URL |
|---|---|---|
| Lilu.kext | 1.6.7 | https://github.com/acidanthera/Lilu/releases |
| VirtualSMC.kext | 1.3.2 | https://github.com/acidanthera/VirtualSMC/releases |
| SMCProcessor.kext | 1.3.2 | https://github.com/acidanthera/VirtualSMC/releases |
| SMCSuperIO.kext | 1.3.2 | https://github.com/acidanthera/VirtualSMC/releases |
| WhateverGreen.kext | 1.3.2 | https://github.com/acidanthera/WhateverGreen/releases |
| AppleALC.kext | 1.9.0 | https://github.com/acidanthera/AppleALC/releases |
| IntelMausi.kext | 1.0.7 | https://github.com/acidanthera/IntelMausi/releases |

### Tools
| Name | Version | URL |
|---|---|---|
| OpenShell.efi | 1.0.0 | https://github.com/acidanthera/OpenCorePkg/releases |
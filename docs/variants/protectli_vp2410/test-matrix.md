# Test matrix

## About

The test matrix is used to determine the scope of tests which the DUT is
subjected from before the release of the new binary.

## Module: Dasharo compatibility

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:----:|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [Memory HCL][HCL]                                 | HCL           | All                                  |
| 2.   | [UEFI compatible interface][EFI]                  | EFI           | EFI001.001                           |
| 3.   | [Display ports][DSP]                              | DSP           | DSP002.001, DSP002.003, DSP003.001, DSP003.003 |
| 4.   | [Network boot][PXE]                               | PXE           | PXE007.001                           |
| 6.   | [Custom logo][CLG]                                | CLG           | All                                  |
| 7.   | [Custom boot menu key][CBK]                       | CBK           | All                                  |
| 8.   | [USB HID and MSC Support][USB]                    | USB           | USB001.001, USB001.002, USB002.001, USB002.002 |
| 9.   | [FreeBSD support][BSD]                            | BSD           | All                                  |
| 10.  | [Debian Stable and Ubuntu LTS support][LBT]       | LBT           | LBT003.001, LBT003.002, LBT004.001, LBT004.002|
| 11.  | [USB-C/Thunderbolt][UTC]                          | UTC           | UTC004.001                           |
| 12.  | [M.2 WiFi/Bluetooth][WLE]                         | WLE           | WLE001.001, WLE002.001, WLE003.001   |
| 13.  | [miniPCIe LTE/WiFi/Bluetooth][MWL]                | MWL           | MWL001.001, MWL002.001, MWL003.001, MWL004.001 |
| 14.  | [eMMC support][MMC]                               | MMC           | MMC001.001                           |
| 15.  | [SMBIOS][DMI]                                     | DMI           | DMI002.001, DMI003.001, DMI004.001, DMI005.001, DMI006.001 |
| 16.  | [Custom network boot entries][CNB]                | CNB           | CNB001.002                           |

[HCL]: ../../unified-test-documentation/dasharo-compatibility/301-memory-hcl.md
[EFI]: ../../unified-test-documentation/dasharo-compatibility/30M-uefi-compatible-interface.md
[DSP]: ../../unified-test-documentation/dasharo-compatibility/31E-display-ports-and-lcd.md
[PXE]: ../../unified-test-documentation/dasharo-compatibility/315-network-boot.md
[CLG]: ../../unified-test-documentation/dasharo-compatibility/304-custom-logo.md
[CBK]: ../../unified-test-documentation/dasharo-compatibility/303-custom-boot-menu-key.md
[USB]: ../../unified-test-documentation/dasharo-compatibility/306-usb-hid-and-msc-support.md
[BSD]: ../../unified-test-documentation/dasharo-compatibility/307-freebsd-support.md
[LBT]: ../../unified-test-documentation/dasharo-compatibility/308-debian-stable-and-ubuntu-lts-support.md
[UTC]: ../../unified-test-documentation/dasharo-compatibility/31H-usb-type-c.md
[WLE]: ../../unified-test-documentation/dasharo-compatibility/318-m2-wifi-bluetooth.md
[MWL]: ../../unified-test-documentation/dasharo-compatibility/31K-minipcie-verification.md
[MMC]: ../../unified-test-documentation/dasharo-compatibility/31M-emmc-support.md
[DMI]: ../../unified-test-documentation/dasharo-compatibility/31L-smbios.md
[CNB]: ../../unified-test-documentation/dasharo-compatibility/30A-custom-network-boot-entries.md

## Module: Dasharo security

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:-----|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [TPM Support][TPM]                                | TPM           | TPM001.001                           |

[TPM]: ../../unified-test-documentation/dasharo-security/200-tpm-support.md

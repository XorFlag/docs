# Test matrix - Asus KGPE-A16

## About

The test matrix is used to determine the scope of tests which the DUT is
subjected from before the release of the new binary.

## Module: Dasharo compatibility

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:-----|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [coreboot base port][CBP]                         | CBP           | All                                  |
| 2.   | [SMBIOS][DMI]                                     | DMI           | DMI001.001, DMI002.001, DMI003.001, DMI004.001|
| 3.   | [coreboot fan control][FAN]                       | FAN           | All                                  |
| 4.   | [Custom boot menu key][CBK]                       | CBK           | All                                  |
| 5.   | [Debian Stable and Ubuntu LTS support][LBT]       | LBT           | LBT002.001                           |
| 6.   | [Network boot][PXE]                               | PXE           | All                                  |
| 7.   | [USB detection][USB]                              | USB           | All                                  |
| 8.   | [USB booting][UBB]                                | UBB           | All                                  |
| 9.   | [Platform suspend and resume][SUSP]               | SUSP          | All                                  |
| 10.  | [Flash write protection][HWP]                     | HWP           | All                                  |
| 11.  | [Display ports and LCD support][DSP]              | DSP           | DSP004.001, DSP004.002               |

[CBP]: ../../unified-test-documentation/dasharo-compatibility/100-coreboot-base-port.md
[DMI]: ../../unified-test-documentation/dasharo-compatibility/31L-smbios.md
[FAN]: ../../unified-test-documentation/dasharo-compatibility/S31-coreboot-fan-control.md
[CBK]: ../../unified-test-documentation/dasharo-compatibility/303-custom-boot-menu-key.md
[LBT]: ../../unified-test-documentation/dasharo-compatibility/308-debian-stable-and-ubuntu-lts-support.md
[PXE]: ../../unified-test-documentation/dasharo-compatibility/315-network-boot.md
[USB]: ../../unified-test-documentation/dasharo-compatibility/31O-usb-detect.md
[UBB]: ../../unified-test-documentation/dasharo-compatibility/31N-usb-boot.md
[SUSP]: ../../unified-test-documentation/dasharo-compatibility/31M-platform-suspend-and-resume.md
[HWP]: ../../unified-test-documentation/dasharo-compatibility/31P-flash-write-protection.md
[DSP]: ../../unified-test-documentation/dasharo-compatibility/31E-display-ports-and-lcd.md

## Module: Dasharo security

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:-----|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [TPM Support][TPM]                                | TPM           | TPM001.001                           |
| 2.   | [Verified Boot support][VBO]                      | VBO           | VBO001.001, VBO002.001, VBO003.001   |

[TPM]: ../../unified-test-documentation/dasharo-security/200-tpm-support.md
[VBO]: ../../unified-test-documentation/dasharo-security/201-verified-boot.md

## Module: Dasharo performance

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:-----|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [coreboot bring up time measurement][CBMEM]       | CBMEM         | All                                  |

[CBMEM]: ../../unified-test-documentation/dasharo-performance/400-coreboot-boot-measure.md
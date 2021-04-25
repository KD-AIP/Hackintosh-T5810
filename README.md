# OpenCore EFI for Dell Precision Tower 5810 updated for Catalina
## OpenCore 0.6.8
### Specs:
  - Intel Xeon E5-1620v3
  - NVIDIA Quadro K4200 4GB GPU
  - 32GB(8GB x 4) 2133MHz DDR4 ECC
  - 512GB SSD / 1TB HDD
  - TL-WN725N Wifi Card
  - Realtek ALC3220(ALC280)
  - DELL SE2416H 24" Display

   
 ### What works:
 - WiFi(added kext for TL-WN725N)
 - native USB3
 - native power management
 - wired Ethernet
 - Sleep/Wake
 - iMessage & Facetime
 - Play Chime(just same like a real Mac :v)

### What doesn't works:
 - audio => solution: using usb sound card
### Setup SMBIOS:

1. Download [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator) (OCC) 
2. Watch [this video](https://drive.google.com/file/d/1KQC-r6yeYCRDAIKaIzWl3wMfrxHkTcCz/view?usp=drivesdk) to know how to UPDATE SMBIOS "the right way"
3. In the list, select `iMacPro1,1`

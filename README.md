# 8.1L_Hackintosh_MS-H610ITX_I5-12400F_RX6750GRE

Everything works fine except Sidecar

<img src="https://github.com/user-attachments/assets/5431164f-b5d1-4285-ac54-3a511bdc3e80" width="290" height="387" />

## Configuration

| Component   | Specification                  | Price/CNY |
|-------------|--------------------------------|-----------|
| Motherboard | MAXSUN Challenger H610ITX 2.5G | 519       |
| CPU         | Intel i5-12400F                | 838       |
| CPU Rad     | Thermalright XP90-X53          | 129       |
| GPU         | PowerColor RX6750GRE 12G-F     | 2017      |
| SSD         | Kioxia RC20 1T                 | 329       |
| SSD Rad     | Thermalright HR-09             | 37        |
| RAM         | Gloway DDR4 3200MHz 16G *2     | 345       |
| WiFi & BT   | BCM943602CS & NGFF Adapter     | 77        |
| PSU         | Almordor SFX650                | 377       |
| Case        | SHINY SNAKE S300 8.1L          | 248       |
| Case Fans   | Thermalright 8015*2 &12025     | 106       |
|- |- | |
| BIOS        | E1.6G                          |           |
| Bootloader  | OpenCore 0.9.5                 |           |
| SMBIOS      | MacPro7,1                      |           |
| OS          | Ventura 13.6.1 & Win 11        |           |

## Bios Settings

- Advanced
	 - CPU Configuration
	 	 - :o: Hyper-Threading 
	 - PCI Subsystem settings
	 	 - PCIe Speed: [Gen3]
	 	 - :o: Above 4G Decoding 
	 	 - :o: Re-size BAR Support 
	 - Trusted Computing
	 	 - :x: Security Device Support 
	 - NCT5585D Super IO Computing
	 	 - :x: Serial Port 1 Configuration
	 - USB Configuration
	 	 - :o: XHCI Hand-off 
- Power
	 - Power Management Configuration
	 	 - :o: Wake on USB 
- Turbo
	 - :x: CFG Lock 
	 - Memory Frequency: [3200MHz]
- Stratup
	 - :x: CSM support 
	 - :x: Fast Boot 
	 - Boot Option #1: [OpenCore]
- Security
	 - :x: Secure Boot
## Tests

<img src="https://github.com/user-attachments/assets/f4658397-92a0-47ca-8d44-0175740603b9" width="425" height="425" />
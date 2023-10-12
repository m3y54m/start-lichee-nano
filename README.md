# Getting started with Sipeed Lichee Nano Board

Lichee Nano is an SD Card Sized Linux Development Board Powered by Allwinner F1C100s ARM9 Processor.

![Lichee Nano 22](https://github.com/m3y54m/start-lichee-nano/assets/1549028/81202e3a-9422-4796-94ae-4c710f5b97d1)

![Lichee Nano Pin](https://github.com/m3y54m/start-lichee-nano/assets/1549028/0c55f675-7a9b-4e20-b394-b7b9f1700098)

## Specification

CPU:

- Allwinner F1C100s, ARM 926EJS processor,up to 900MHz

Memory & Storage:

- 32MB DDR integrated into SoC, 16MB SPI Flash
- Onboard microSD card slot (can boot from microSD card)

Display:

- 40-pin RGB LCD FPC connector supporting 272×480, 480×800, 1024×600 (and other resolutions resistive and capacitive displays trough the adapter board)
- Support 720P video output, support video stream decoding such as H.264 / MPEG

Communication Interface:

- SDIO for WiFi module
- SPI x2, TWI x3, UART x3
- OTG USB x1, TV out

Other Interfaces:

- PWM x2, LRADC x1
- Headphone output x2, Mic x1

Electrical characteristics:

- Input: 5V via micro USB port, 3.3 to 5V via pin
- Output: 3.3V, selectable input RTC voltage
- Power Consumption: 54mA (idle) with Linux, 250mA with display
- Storage temperature: -40 ~ 125°C
- Operating temperature: -20 ~ 70°C

Software and development environment:

- Support 3.10 BSP linux,
- Support 4.19 mainline linux,
- Support xboot bare metal development environment
- Support RT-Thread

Notes:

- Requires microSD card (or soldering SPI flash) to boot
- The serial port for system debugging is UART0 (displayed as U0: Tx Rx on silk)

## Schematics

[lichee_nano_8.16(Schematic).pdf](https://dl.sipeed.com/LICHEE/Nano/HDK/lichee_nano_8.16(Schematic).pdf)

![lichee_nano_8 16(Schematic)](https://github.com/m3y54m/start-lichee-nano/assets/1549028/b377ce86-945f-4386-91a0-9641ca588b4e)

## Development Materials

- [Lichee-Pi GitHub](https://github.com/Lichee-Pi)
- [Lichee Nano - Docs](https://github.com/Lichee-Pi/Lichee-Nano-Doc-us-english)
- [Lichee Nano - SDK](https://dl.sipeed.com/fileDownload?verify_code=fdpo&file_url=LICHEE/Nano/SDK/licheepi-nano-docker-v1_0.tgz)
- [Lichee Nano - Image](https://files.seeedstudio.com/products/102110201/Lichee%20Nano/%E9%95%9C%E5%83%8F/openwrt_sunxi_arm9_suniv_f1c100s.gz)

## Resources

- [Sipeed Lichee Nano Linux Development Board - Seeed Studio](https://www.seeedstudio.com/Sipeed-Lichee-Nano-Linux-Development-Board-16M-Flash-WiFi-Version-p-2893.html)

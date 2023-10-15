# Getting started with Sipeed Lichee Nano board

Lichee Nano is an SD card sized Linux development board powered by Allwinner F1C100s ARM9 processor.

![image](https://github.com/m3y54m/start-lichee-nano/assets/1549028/eda67f6c-af07-466a-9d7e-6571b5eff1e4)

![Lichee Nano Pin](https://github.com/m3y54m/start-lichee-nano/assets/1549028/0c55f675-7a9b-4e20-b394-b7b9f1700098)

## Specification

![F1C100s](https://github.com/m3y54m/start-lichee-nano/assets/1549028/67e79b4b-9c60-4663-a777-a9551992eeaa)

![image](https://github.com/m3y54m/start-lichee-nano/assets/1549028/e361d6d1-7adb-4e44-b598-3c3c196b11cb)

CPU:

- Allwinner F1C100s, ARM 926EJS processor, up to 900MHz

Memory & Storage:

- 32MB DDR integrated into SoC, 16MB SPI Flash
- Onboard microSD card slot (can boot from microSD card)

Display:

- 40-pin RGB LCD FPC connector supporting 272×480, 480×800, 1024×600 (and other resolutions resistive and capacitive displays trough the adapter board)
- Support 720P video output, support video stream decoding such as H.264 / MPEG

Communication Interface:

- SDIO for WiFi module
- SPI x 2, TWI x 3, UART x 3
- OTG USB x 1, TV out

Other Interfaces:

- PWM x 2, LRADC x 1
- Headphone output x 2, Mic x 1

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

- [Lichee Nano Official Documents (Chinese)](https://wiki.sipeed.com/soft/Lichee/zh/Nano-Doc-Backup/index.html)
- [Lichee Nano Official Development Materials (HDK / SDK / Document / Image)](https://dl.sipeed.com/shareURL/LICHEE/Nano)
- [Lichee Nano Official Development Materials (HDK / SDK / Document / Image) - Mirror on MEGA.NZ](https://mega.nz/folder/A8g1Hb4J#WcuoqvbpasKlVB8-YEpWPA/folder/9ppSVKhC)
- [XBOOT - The extensible bootloader for embedded system with application engine](https://xboot.org/xboot/)
- [XFEL - Tiny FEL tools for Allwinner SOC](https://xboot.org/xfel/)
- [Building a Linux image for Lichee Nano from scratch](https://github.com/haoliver/lichee-nano)
- [How to enter FEL mode on Lichee nano](https://gist.github.com/squeuei/280339368e85b9faf4d756aad8171379)

## Resources

### English

- [Sipeed Lichee Nano Linux Development Board - Seeed Studio](https://www.seeedstudio.com/Sipeed-Lichee-Nano-Linux-Development-Board-16M-Flash-WiFi-Version-p-2893.html)
- [Using F1C100s SoCs with Linux with comparable cost as microcontrollers](https://blog.expertise.dev/2021-04-29-Using-F1C100s-SoCs-with-Linux-with-comparable-cost-as-microcontrollers/)
- [Building Buildroot & linux on Allwinner F1C100S](https://qyx.krtko.org/tutorials/f1c100s.html)
- [Setting up embedded Linux on Lichee Pi Nano](https://unframework.com/2020/05/27/setting-up-embedded-linux-on-lichee-pi-nano/)
- [My Business Card Runs Linux](https://www.thirtythreeforty.net/posts/2019/12/my-business-card-runs-linux/)
- [A Buildroot distribution small enough to run on my business card](https://github.com/thirtythreeforty/businesscard-linux)
- [Lichee-Nano-Doc-us-english](https://github.com/Lichee-Pi/Lichee-Nano-Doc-us-english)
- [F1C100s - linux-sunxi.org](https://linux-sunxi.org/F1C100s)
- [F1C100s Datasheet V1.0](https://linux-sunxi.org/images/b/ba/F1C100s_Datasheet_V1.0.pdf)
- [Allwinner F1C200s User Manual V1.2.pdf](https://linux-sunxi.org/images/5/56/Allwinner_F1C200s_User_Manual_V1.2.pdf)
- [Config files for full Lichee Pi Nano Linux image build](https://github.com/unframework/licheepi-nano-buildroot)
- [Yocto meta-layer for Lichee Pi Nano ](https://github.com/voloviq/meta-licheepinano)
- [Lichee Pi Nano Buildroot External Tree](https://github.com/florpor/licheepi-nano)
- [play with allwinner f1c100s/f1c200s](https://github.com/suda-morris/suda-f1c100s)
- [Linux for the Hantek DSO2000 series using Buildroot](https://github.com/AndrewBCN/Hantek_DSO2x1x_Linux)
- [Low-level libraries and bare metal projects for allwinner F1C100s SOC](https://github.com/nminaylov/F1C100s_projects)

### Persian / فارسی

<div dir="rtl">

- [امبدد لینوکس – قسمت دهم – ضمیمه راه اندازی سخت افزار (بخش ششم)](https://sisoog.com/2020/09/21/%d8%a7%d9%85%d8%a8%d8%af%d8%af-%d9%84%db%8c%d9%86%d9%88%da%a9%d8%b3-%d9%82%d8%b3%d9%85%d8%aa-%d8%af%d9%87%d9%85-%d8%b6%d9%85%db%8c%d9%85%d9%87-%d8%b1%d8%a7%d9%87-%d8%a7%d9%86%d8%af/)
- [کار با تراشه F1C100S – قسمت دوم – مقدمه ای بر buildroot](https://sisoog.com/2022/01/04/buildroot/)
- [کار با تراشه F1C100S – قسمت سوم – ساخت ایمیج](https://sisoog.com/2022/01/12/%da%a9%d8%a7%d8%b1-%d8%a8%d8%a7-%d8%aa%d8%b1%d8%a7%d8%b4%d9%87-f1c100s-%d9%82%d8%b3%d9%85%d8%aa-%d8%b3%d9%88%d9%85-%d8%b3%d8%a7%d8%ae%d8%aa-%d8%a7%db%8c%d9%85%db%8c%d8%ac/)
- [کار با تراشه F1C100S – قسمت پنجم – راه اندازی وای فای (wifi)](https://sisoog.com/2023/05/25/f1c100s-rtl-wifi/)
- [کار با f1c100s بدون سیستم عامل (BareMetal) – قسمت اول](https://sisoog.com/2022/09/11/f1c100s-baremetal/)

</div>

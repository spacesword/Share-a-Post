![Raspberry](https://images-na.ssl-images-amazon.com/images/I/810xXvVWWwL._SX466_.jpg)

# Raspberry Pi
The Raspberry Pi is a series of small single-board computers developed in the United Kingdom by the Raspberry Pi Foundation to promote the teaching of basic computer
 science in schools and in developing countries.The original model became far more popular than anticipated, selling outside its target market for uses 
such as robotics.It does not include peripherals (such as keyboards and mice) and cases. However, some accessories have been included in several official and 
unofficial bundles.

The organisation behind the Raspberry Pi consists of two arms. The first two models were developed by the Raspberry Pi Foundation. After the Pi Model B was released,
the Foundation set up Raspberry Pi Trading, with Eben Upton as CEO, to develop the third model, the B+. Raspberry Pi Trading is responsible for developing the 
technology while the Foundation is an educational charity to promote the teaching of basic computer science in schools and in developing countries.

According to the Raspberry Pi Foundation, more than 5 million Raspberry Pis were sold by February 2015, making it the best-selling British computer.[9] By November 
2016 they had sold 11 million units,and 12.5m by March 2017, making it the third best-selling "general purpose computer".[12] In July 2017, sales reached nearly 
15 million. In March 2018, sales reached 19 millionMost Pis are made in a Sony factory in Pencoed, Wales[14]; some are made in China or Japan.

**Contents**
1.Generations of released models
2.Hardware
  2.1.Processor
    2.1.1.Performance
    2.1.2.Overclocking
  2.2.RAM
  2.3.Networking
  2.4.Peripherals
  2.5.Video
  2.6.Real-time clock
  2.7.Accessories


## **Generations of released models:**
Several generations of Raspberry Pis have been released. All models feature a Broadcom system on a chip (SoC) with an integrated ARM-compatible central processing 
unit (CPU) and on-chip graphics processing unit (GPU).Processor speed ranges from 700 MHz to 1.4 GHz for the Pi 3 Model B+; on-board memory ranges from 256 MB to 1 
GB RAM. Secure Digital (SD) cards are used to store the operating system and program memory in either SDHC or MicroSDHC sizes. The boards have one to four USB ports.
 For video output, HDMI and composite video are supported, with a standard 3.5 mm tip-ring-sleeve jack for audio output. Lower-level output is provided by a number 
of GPIO pins, which support common protocols like I²C. The B-models have an 8P8C Ethernet port and the Pi 3 and Pi Zero W have on-board Wi-Fi 802.11n and Bluetooth.
 Prices range from US$5 to $35
The first generation (Raspberry Pi 1 Model B) was released in February 2012, followed by the simpler and cheaper Model A. In 2014, the Foundation released a board 
with an improved design, Raspberry Pi 1 Model B+. These boards are approximately credit-card sized and represent the standard mainline form-factor. Improved A+ and 
B+ models were released a year later. A "Compute Module" was released in April 2014 for embedded applications. The Raspberry Pi 2, which added more RAM, was released
 in February 2015.
A Raspberry Pi Zero with smaller size and reduced input/output (I/O) and general-purpose input/output (GPIO) capabilities was released in November 2015 for US$5. By 
2017, it became the newest mainline Raspberry Pi. On 28 February 2017, the Raspberry Pi Zero W was launched, a version of the Zero with Wi-Fi and Bluetooth 
capabilities, for US$10.[16][17] On 12 January 2018, the Raspberry Pi Zero WH was launched, the same version of the Zero W with pre-soldered GPIO headers.
Raspberry Pi 3 Model B was released in February 2016 with a 64 bit quad core processor, on-board WiFi, Bluetooth and USB boot capabilities.[19] On Pi Day 2018 model 
3B+ appeared with a faster 1.4 GHz processor and a three times faster network based on gigabit Ethernet (300 Mbit / s) or 2.4 / 5 GHz dual-band Wi-Fi (100 Mbit / s)
.Other options are: Power over Ethernet (PoE), USB boot and network boot (an SD card is no longer required). This allows the use of the Pi in hard-to-reach places
 (possibly without electricity).
 

## Hardware:
The Raspberry Pi hardware has evolved through several versions that feature variations in memory capacity and peripheral-device support.
This block diagram describes Model B and B+; Model A, A+, and the Pi Zero are similar, but lack the Ethernet and USB hub components. The Ethernet adapter is internally
 connected to an additional USB port. In Model A, A+, and the Pi Zero, the USB port is connected directly to the system on a chip (SoC). On the Pi 1 Model B+ and 
later models the USB/Ethernet chip contains a five-port USB hub, of which four ports are available, while the Pi 1 Model B only provides two. On the Pi Zero, the USB 
port is also connected directly to the SoC, but it uses a micro USB (OTG) port.

### 1) Processor:The Broadcom BCM2835 SoC used in the first generation Raspberry Pi[20] includes a 700 MHz ARM1176JZF-S processor, VideoCore IV graphics processing unit 
(GPU),[21] and RAM. It has a level 1 (L1) cache of 16 KB and a level 2 (L2) cache of 128 KB. The level 2 cache is used primarily by the GPU. The SoC is stacked 
underneath the RAM chip, so only its edge is visible. The 1176JZ(F)-S is the same CPU used in the original iPhone,[22] although at a higher clock rate, and mated with
 a much faster GPU. 
The earlier V1.1 model of the Raspberry Pi 2 used a Broadcom BCM2836 SoC with a 900 MHz 32-bit quad-core ARM Cortex-A7 processor, with 256 KB shared L2 cache.[23] The
raspberry Pi 2 V1.2 was upgraded to a Broadcom BCM2837 SoC with a 1.2 GHz 64-bit quad-core ARM Cortex-A53 processor,[24] the same SoC which is used on the Raspberry Pi
3, but underclocked (by default) to the same 900 MHz CPU clock speed as the V1.1. The BCM2836 SoC is no longer in production (as of late 2016). 
The Raspberry Pi 3+ uses a Broadcom BCM2837B0 SoC with a 1.4 GHz 64-bit quad-core ARM Cortex-A53 processor, with 512 KB shared L2 cache.[1] 

a) **Performance:**While operating at 700 MHz by default, the first generation Raspberry Pi provided a real-world performance roughly equivalent to 0.041 GFLOPS.[25][26] 
On the CPU level the performance is similar to a 300 MHz Pentium II of 1997–99. The GPU provides 1 Gpixel/s or 1.5 Gtexel/s of graphics processing or 24 GFLOPS of 
general purpose computing performance. The graphical capabilities of the Raspberry Pi are roughly equivalent to the performance of the Xbox of 2001. 
Raspberry Pi 2 V1.1 included a quad-core Cortex-A7 CPU running at 900 MHz and 1 GB RAM. It was described as 4–6 times more powerful than its predecessor. The GPU was
 identical to the original.[23] In parallelised benchmarks, the Raspberry Pi 2 V1.1 could be up to 14 times faster than a Raspberry Pi 1 Model B+.[27] 
The Raspberry Pi 3, with a quad-core ARM Cortex-A53 processor, is described as having ten times the performance of a Raspberry Pi 1.[28] This was suggested to be 
highly dependent upon task threading and instruction set use. Benchmarks showed the Raspberry Pi 3 to be approximately 80% faster than the Raspberry Pi 2 in 
parallelised tasks    
 
b) **Overclocking:** Most Raspberry Pi chips could be overclocked to 800 MHz, and some to 1000 MHz. There are reports the Raspberry Pi 2 can be similarly overclocked, in 
extreme cases, even to 1500 MHz (discarding all safety features and over-voltage limitations). In the Raspbian Linux distro the overclocking options on boot can be 
done by a software command running "sudo raspi-config" without voiding the warranty.[30] In those cases the Pi automatically shuts the overclocking down if the chip 
temperature reaches 85 °C (185 °F), but it is possible to override automatic over-voltage and overclocking settings (voiding the warranty); an appropriately sized heat
 sink is needed to protect the chip from serious overheating. 
Newer versions of the firmware contain the option to choose between five overclock ("turbo") presets that when used, attempt to maximise the performance of the SoC 
without impairing the lifetime of the board. This is done by monitoring the core temperature of the chip and the CPU load, and dynamically adjusting clock speeds and 
the core voltage. When the demand is low on the CPU or it is running too hot the performance is throttled, but if the CPU has much to do and the chip's temperature is 
acceptable, performance is temporarily increased with clock speeds of up to 1 GHz, depending on the individual board and on which of the turbo settings is used. 
The seven overclock presets are: 
none; 700 MHz ARM, 250 MHz core, 400 MHz SDRAM, 0 overvolting
modest; 800 MHz ARM, 250 MHz core, 400 MHz SDRAM, 0 overvolting,
medium; 900 MHz ARM, 250 MHz core, 450 MHz SDRAM, 2 overvolting,
high; 950 MHz ARM, 250 MHz core, 450 MHz SDRAM, 6 overvolting,
turbo; 1000 MHz ARM, 500 MHz core, 600 MHz SDRAM, 6 overvolting,
Pi 2; 1000 MHz ARM, 500 MHz core, 500 MHz SDRAM, 2 overvolting,
Pi 3; 1100 MHz ARM, 550 MHz core, 500 MHz SDRAM, 6 overvolting. In system information the CPU speed will appear as 1200 MHz. When idling, speed lowers to 600 MHz.[30][31]
In the highest (turbo) preset the SDRAM clock was originally 500 MHz, but this was later changed to 600 MHz because 500 MHz sometimes causes SD card corruption. 
Simultaneously in high mode the core clock speed was lowered from 450 to 250 MHz, and in medium mode from 333 to 250 MHz. 
The Raspberry Pi Zero runs at 1 GHz. 
The CPU on the first and second generation Raspberry Pi board did not require cooling, such as a heat sink or fan, even when overclocked, but the Raspberry Pi 3 may 
generate more heat when overclocked.[32]
 
### 2) RAM:On the older beta Model B boards, 128 MB was allocated by default to the GPU, leaving 128 MB for the CPU.[33] On the first 256 MB release Model B (and Model A), 
three different splits were possible. The default split was 192 MB (RAM for CPU), which should be sufficient for standalone 1080p video decoding, or for simple 3D, but
 probably not for both together. 224 MB was for Linux only, with only a 1080p framebuffer, and was likely to fail for any video or 3D. 128 MB was for heavy 3D, 
possibly also with video decoding (e.g. XBMC).[34] Comparatively the Nokia 701 uses 128 MB for the Broadcom VideoCore IV.[35] 
For the later Model B with 512 MB RAM new standard memory split files (arm256_start.elf, arm384_start.elf, arm496_start.elf) were initially released for 256 MB, 384 MB
 and 496 MB CPU RAM (and 256 MB, 128 MB and 16 MB video RAM) respectively. But a week or so later the RPF released a new version of start.elf that could read a new 
entry in config.txt (gpu_mem=xx) and could dynamically assign an amount of RAM (from 16 to 256 MB in 8 MB steps) to the GPU, so the older method of memory splits 
became obsolete, and a single start.elf worked the same for 256 MB and 512 MB Raspberry Pis.[36] 
The Raspberry Pi 2 and the Raspberry Pi 3 have 1 GB of RAM.[37][38] The Raspberry Pi Zero and Zero W have 512 MB of RAM.

### 3) Networking:The Model A, A+ and Pi Zero have no Ethernet circuitry and are commonly connected to a network using an external user-supplied USB Ethernet or Wi-Fi 
adapter. On the Model B and B+ the Ethernet port is provided by a built-in USB Ethernet adapter using the SMSC LAN9514 chip.[39] The Raspberry Pi 3 and Pi Zero W 
(wireless) are equipped with 2.4 GHz WiFi 802.11n (150 Mbit/s) and Bluetooth 4.1 (24 Mbit/s) based on the Broadcom BCM43438 FullMAC chip with no official support for 
monitor mode but implemented through unofficial firmware patching[40] and the Pi 3 also has a 10/100 Mbit/s Ethernet port. The Raspberry Pi 3B+ features dual-band IEEE
 802.11b/g/n/ac WiFi, Bluetooth 4.2, and Gigabit Ethernet (limited to approximately 300 Mbit/s by the USB 2.0 bus between it and the SoC). 

### 4) Peripherals:The Raspberry Pi may be operated with any generic USB computer keyboard and mouse.[41] It may also be used with USB storage, USB to MIDI converters, 
and virtually any other device/component with USB capabilities. 
Other peripherals can be attached through the various pins and connectors on the surface of the Raspberry Pi.

### 5) **video:** The video controller can generate standard modern TV resolutions, such as HD and Full HD, and higher or lower monitor resolutions as well as older NTSC or PAL
 standard CRT TV resolutions. As shipped (i.e., without custom overclocking) it can support the following resolutions: 640×350 EGA; 640×480 VGA; 800×600 SVGA; 1024×768
 XGA; 1280×720 720p HDTV; 1280×768 WXGA variant; 1280×800 WXGA variant; 1280×1024 SXGA; 1366×768 WXGA variant; 1400×1050 SXGA+; 1600×1200 UXGA; 1680×1050 WXGA+; 1920
×1080 1080p HDTV; 1920×1200 WUXGA.[43] 
Higher resolutions, up to 2048×1152, may work[44][45] or even 3840×2160 at 15 Hz (too low a frame rate for convincing video).[46] Note also that allowing the highest
 resolutions does not imply that the GPU can decode video formats at these resolutions; in fact, the Pis are known to not work reliably for H.265 (at those high 
resolutions), commonly used for very high resolutions (however, most common formats up to Full HD do work). 
Although the Raspberry Pi 3 does not have H.265 decoding hardware, the CPU is more powerful than its predecessors, potentially fast enough to allow the decoding of 
H.265-encoded videos in software.[47] The GPU in the Raspberry Pi 3 runs at higher clock frequencies of 300 MHz or 400 MHz, compared to previous versions which ran at 
250 MHz.[48] 
The Raspberry Pis can also generate 576i and 480i composite video signals, as used on old-style (CRT) TV screens and less-expensive monitors through standard 
connectors – either RCA or 3.5 mm phono connector depending on models. The television signal standards supported are PAL-BGHID, PAL-M, PAL-N, NTSC and NTSC-J.[49] 

### 6)Real-time clock:None of the current Raspberry Pi models have a built-in real-time clock, so they are unable to keep track of the time of day independently. As a workaround, 
a program
 running on the Pi can retrieve the time from a network time server or from user input at boot time, thus knowing the time while powered on. To provide consistency of
 time for the file system, the Pi automatically saves the current system time on shutdown, and re-loads that time at boot. 
A real-time hardware clock with battery backup, such as the DS1307, may be added (often via the I²C interface). 

### 7)Accessories:Gertboard – A Raspberry Pi Foundation sanctioned device, designed for educational purposes, that expands the Raspberry Pi's GPIO pins to allow interface 
with and control of LEDs, switches, analogue signals, sensors and other devices. It also includes an optional Arduino compatible controller to interface with the Pi.
[96]
Camera – On 14 May 2013, the foundation and the distributors RS Components & Premier Farnell/Element 14 launched the Raspberry Pi camera board alongside a firmware 
update to accommodate it.[97] The camera board is shipped with a flexible flat cable that plugs into the CSI connector which is located between the Ethernet and HDMI 
ports. In Raspbian, the user must enable the use of the camera board by running Raspi-config and selecting the camera option. The camera module costs €20 in Europe (9
 September 2013).[98] It can produce 1080p, 720p and 640x480p video. The dimensions are 25 mm × 20 mm × 9 mm.[98] In May 2016, v2 of the camera came out, and is an 8 
megapixel camera.
Infrared Camera – In October 2013, the foundation announced that they would begin producing a camera module without an infrared filter, called the Pi NoIR.[99]
Official Display – On 8 September 2015, The foundation and the distributors RS Components & Premier Farnell/Element 14 launched the Raspberry Pi Touch Display[100]
HAT (Hardware Attached on Top) expansion boards – Together with the Model B+, inspired by the Arduino shield boards, the interface for HAT boards was devised by the 
Raspberry Pi Foundation. Each HAT board carries a small EEPROM (typically a CAT24C32WI-GT3)[101] containing the relevant details of the board,[102] so that the 
Raspberry Pi's OS is informed of the HAT, and the technical details of it, relevant to the OS using the HAT.[103] Mechanical details of a HAT board, which uses the 
four mounting holes in their rectangular formation, are available online.


## author

**Muskan Sanghai**

**email:**[muskansanghai@gmail.com](mailto:muskansanghai@gmail.com)



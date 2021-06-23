---<<BOOT>>---
GDB: debug ports: uart
GDB: current port: uart
KDB: debugger backends: ddb gdb
KDB: current backend: ddb
                   Type     Physical      Virtual   #Pages Attr
         MemoryMappedIO 000001e88180 000001e88180 00000001 RUNTIME
     ConventionalMemory 000080000000 000080000000 00007efa WB 
       BootServicesData 000087efa000 000087efa000 0000000c WB 
     ConventionalMemory 000087f06000 000087f06000 0006ec21 WB 
    RuntimeServicesData 0000f6b27000 0000f6b27000 00000001 WB RUNTIME
             LoaderData 0000f6b28000 0000f6b28000 00005208 WB 
    RuntimeServicesCode 0000fbd30000 0000fbd30000 00000010 WB RUNTIME
             LoaderData 0000fbd40000 0000fbd40000 000000c0 WB 
     ConventionalMemory 002080000000 002080000000 00ef7eb3 WB 
             LoaderData 002f77eb3000 002f77eb3000 00008001 WB 
             LoaderCode 002f7feb4000 002f7feb4000 00000135 WB 
               Reserved 002f7ffe9000 002f7ffe9000 00000005 WB 
       BootServicesData 002f7ffee000 002f7ffee000 00000003 WB 
               Reserved 002f7fff1000 002f7fff1000 00000008 WB 
       BootServicesData 002f7fff9000 002f7fff9000 00000002 WB 
    RuntimeServicesData 002f7fffb000 002f7fffb000 00000001 WB RUNTIME
               Reserved 002f7fffc000 002f7fffc000 00000002 WB 
    RuntimeServicesData 002f7fffe000 002f7fffe000 00000001 WB RUNTIME
               Reserved 002f7ffff000 002f7ffff000 00000001 WB 
Physical memory chunk(s):
  0x80000000 - 0xfbd2ffff,  1981 MB ( 507184 pages)
  0xfbd40000 - 0xfbdfffff,     0 MB (    192 pages)
  0x2080000000 - 0x2f7ffe8fff, 61439 MB (15728617 pages)
  0x2f7ffee000 - 0x2f7fff0fff,     0 MB (      3 pages)
  0x2f7fff9000 - 0x2f7fffbfff,     0 MB (      3 pages)
  0x2f7fffe000 - 0x2f7fffefff,     0 MB (      1 pages)
Excluded memory regions:
  0x01e88000 - 0x01e89fff,     0 MB (      2 pages) NoAlloc 
  0xf6b27000 - 0xf6b27fff,     0 MB (      1 pages) NoAlloc 
  0xfbd30000 - 0xfbd3ffff,     0 MB (     16 pages) NoAlloc 
  0x2f78000000 - 0x2f794f4fff,    20 MB (   5365 pages) NoAlloc 
  0x2f7ffe9000 - 0x2f7ffedfff,     0 MB (      5 pages) NoAlloc 
  0x2f7fff1000 - 0x2f7fff8fff,     0 MB (      8 pages) NoAlloc 
  0x2f7fffb000 - 0x2f7fffffff,     0 MB (      5 pages) NoAlloc 
Found 16 CPUs in the device tree
Copyright (c) 1992-2021 The FreeBSD Project.
Copyright (c) 1979, 1980, 1983, 1986, 1988, 1989, 1991, 1992, 1993, 1994
	The Regents of the University of California. All rights reserved.
FreeBSD is a registered trademark of The FreeBSD Foundation.
FreeBSD 14.0-CURRENT #0 main-n247405-8fa5c577de3: Thu Jun 17 07:18:21 UTC 2021
    root@releng1.nyi.freebsd.org:/usr/obj/usr/src/arm64.aarch64/sys/GENERIC arm64
FreeBSD clang version 12.0.0 (git@github.com:llvm/llvm-project.git llvmorg-12.0.0-0-gd28af7c654d8)
WARNING: WITNESS option enabled, expect reduced performance.
VT: init without driver.
Preloaded elf kernel "/boot/kernel/kernel" at 0xffff0000012c7000.
Preloaded dtb "/boot/dtb/freescale/fsl-lx2160a-clearfog-cx.dtb" at 0xffff0000012d0118.
module firmware already present!
real memory  = 66502656000 (63421 MB)
Physical memory chunk(s):
0x00000080000000 - 0x000000f6b26fff, 1991405568 bytes (486183 pages)
0x000000f6b28000 - 0x000000fbd2ffff, 86016000 bytes (21000 pages)
0x000000fbd40000 - 0x000000fbdfffff, 786432 bytes (192 pages)
0x00002080000000 - 0x00002f154f2fff, 62634536960 bytes (15291635 pages)
0x00002f794f5000 - 0x00002f7ffe8fff, 112148480 bytes (27380 pages)
0x00002f7ffee000 - 0x00002f7fff0fff, 12288 bytes (3 pages)
0x00002f7fff9000 - 0x00002f7fffafff, 8192 bytes (2 pages)
avail memory = 64822714368 (61819 MB)
Starting CPU 1 (1)
Starting CPU 2 (100)
Starting CPU 3 (101)
Starting CPU 4 (200)
Starting CPU 5 (201)
Starting CPU 6 (300)
Starting CPU 7 (301)
Starting CPU 8 (400)
Starting CPU 9 (401)
Starting CPU 10 (500)
Starting CPU 11 (501)
Starting CPU 12 (600)
Starting CPU 13 (601)
Starting CPU 14 (700)
Starting CPU 15 (701)
FreeBSD/SMP: Multiprocessor System Detected: 16 CPUs
random: no preloaded entropy cache
arc4random: WARNING: initial seeding bypassed the cryptographic random device because it was not yet seeded and the knob 'bypass_before_seeding' was enabled.
VIMAGE (virtualized network stack) enabled
hostuuid: using 00000000-0000-0000-0000-000000000000
ULE: setup cpu 0
ULE: setup cpu 1
ULE: setup cpu 2
ULE: setup cpu 3
ULE: setup cpu 4
ULE: setup cpu 5
ULE: setup cpu 6
ULE: setup cpu 7
ULE: setup cpu 8
ULE: setup cpu 9
ULE: setup cpu 10
ULE: setup cpu 11
ULE: setup cpu 12
ULE: setup cpu 13
ULE: setup cpu 14
ULE: setup cpu 15
snd_unit_init() u=0x00ff8000 [512] d=0x00007c00 [32] c=0x000003ff [1024]
feeder_register: snd_unit=-1 snd_maxautovchans=16 latency=2 feeder_rate_min=1 feeder_rate_max=2016000 feeder_rate_round=25
random: entropy device external interface
firmware: 'tegra210_xusb_fw' version 0: 132608 bytes loaded at 0xffff000000963780
EFI Runtime entry 0 is not aligned
EFI cannot create runtime map
module_register_init: MOD_LOAD (efirt, 0xffff00000015f708, 0) error 12
crypto: <crypto core>
kbd0 at kbdmux0
mem: <memory>
null: <full device, null device, zero device>
openfirm: <Open Firmware control device>
ofwbus0: <Open Firmware Device Tree>
clk_fixed0: <Fixed clock> on ofwbus0
simplebus0: <Flattened device tree simple bus> on ofwbus0
lx2160a_clkgen0: <LX2160A clockgen> mem 0x1300000-0x139ffff on simplebus0
Clock: clockgen_sysclk, parent: sysclk(0), freq: 100000000
Clock: platform_pll, parent: clockgen_sysclk(0), freq: 1400000000
Clock: platform_pll_div1, parent: platform_pll(0), freq: 1400000000
Clock: platform_pll_div2, parent: platform_pll(0), freq: 700000000
Clock: platform_pll_div3, parent: platform_pll(0), freq: 466666666
Clock: platform_pll_div4, parent: platform_pll(0), freq: 350000000
Clock: platform_pll_div5, parent: platform_pll(0), freq: 280000000
Clock: platform_pll_div6, parent: platform_pll(0), freq: 233333333
Clock: platform_pll_div7, parent: platform_pll(0), freq: 200000000
Clock: platform_pll_div8, parent: platform_pll(0), freq: 175000000
Clock: platform_pll_div9, parent: platform_pll(0), freq: 155555555
Clock: platform_pll_div10, parent: platform_pll(0), freq: 140000000
Clock: platform_pll_div11, parent: platform_pll(0), freq: 127272727
Clock: platform_pll_div12, parent: platform_pll(0), freq: 116666666
Clock: platform_pll_div13, parent: platform_pll(0), freq: 107692307
Clock: platform_pll_div14, parent: platform_pll(0), freq: 100000000
Clock: platform_pll_div15, parent: platform_pll(0), freq: 93333333
Clock: platform_pll_div16, parent: platform_pll(0), freq: 87500000
Clock: cga_pll1, parent: clockgen_sysclk(0), freq: 2000000000
Clock: cga_pll1_div2, parent: cga_pll1(0), freq: 1000000000
Clock: cga_pll1_div4, parent: cga_pll1(0), freq: 500000000
Clock: cga_pll2, parent: clockgen_sysclk(0), freq: 2000000000
Clock: cga_pll2_div2, parent: cga_pll2(0), freq: 1000000000
Clock: cga_pll2_div4, parent: cga_pll2(0), freq: 500000000
Clock: cgb_pll1, parent: clockgen_sysclk(0), freq: 2000000000
Clock: cgb_pll1_div2, parent: cgb_pll1(0), freq: 1000000000
Clock: cgb_pll1_div3, parent: cgb_pll1(0), freq: 666666666
Clock: cgb_pll1_div4, parent: cgb_pll1(0), freq: 500000000
Clock: cgb_pll2, parent: clockgen_sysclk(0), freq: 900000000
Clock: cgb_pll2_div2, parent: cgb_pll2(0), freq: 450000000
Clock: cgb_pll2_div3, parent: cgb_pll2(0), freq: 300000000
Clock: cgb_pll2_div4, parent: cgb_pll2(0), freq: 225000000
Clock: cg-cmux0, parent: cga_pll1(0), freq: 2000000000
Clock: cg-cmux1, parent: cga_pll1(0), freq: 2000000000
Clock: cg-cmux2, parent: cga_pll1(0), freq: 2000000000
Clock: cg-cmux3, parent: cga_pll1(0), freq: 2000000000
Clock: cg-cmux4, parent: cgb_pll1(0), freq: 2000000000
Clock: cg-cmux5, parent: cgb_pll1(0), freq: 2000000000
Clock: cg-cmux6, parent: cgb_pll1(0), freq: 2000000000
Clock: cg-cmux7, parent: cgb_pll1(0), freq: 2000000000
 lx2160a_clkgen_attach: offset: 0x00000080, val: 0x08600428
 lx2160a_clkgen_attach: offset: 0x000000A0, val: 0x08600428
 lx2160a_clkgen_attach: offset: 0x00010080, val: 0x08600428
 lx2160a_clkgen_attach: offset: 0x000100A0, val: 0x08600412
 lx2160a_clkgen_attach: offset: 0x00060080, val: 0x0860041C
 lx2160a_clkgen_attach: offset: 0x000600A0, val: 0x00000000
regfix0: <Fixed Regulator> on ofwbus0
psci0: <ARM Power State Co-ordination Interface Driver> on ofwbus0
psci0: PSCI version 0.2 compatible
gpio0: <Freescale QorIQ GPIO driver> mem 0x2300000-0x230ffff irq 28 on simplebus0
gpiobus0: <GPIO bus> on gpio0
gpio1: <Freescale QorIQ GPIO driver> mem 0x2310000-0x231ffff irq 29 on simplebus0
gpiobus1: <GPIO bus> on gpio1
gpio2: <Freescale QorIQ GPIO driver> mem 0x2320000-0x232ffff irq 30 on simplebus0
gpiobus2: <GPIO bus> on gpio2
gpio3: <Freescale QorIQ GPIO driver> mem 0x2330000-0x233ffff irq 31 on simplebus0
gpiobus3: <GPIO bus> on gpio3
gic0: <ARM Generic Interrupt Controller v3.0> mem 0x6000000-0x600ffff,0x6200000-0x63fffff,0xc0c0000-0xc0c1fff,0xc0d0000-0xc0d0fff,0xc0e0000-0xc0fffff irq 0 on ofwbus0
gic0: SPIs: 288, IDs: 65535
gic0: Start searching for Re-Distributor
gic0: CPU0 Re-Distributor has been found
gic0: CPU0 Re-Distributor woke up
gic0: CPU0 enabled CPU interface via system registers
its0: <ARM GIC Interrupt Translation Service> mem 0x6020000-0x603ffff on gic0
generic_timer0: <ARMv8 Generic Timer> irq 1,2,3,4 on ofwbus0
Timecounter "ARM MPCore Timecounter" frequency 25000050 Hz quality 1000
Event timer "ARM MPCore Eventtimer" frequency 25000050 Hz quality 1000
cpulist0: <Open Firmware CPU Group> on ofwbus0
cpu0: <Open Firmware CPU> on cpulist0
cpu0: Nominal frequency 2000Mhz
cpu1: <Open Firmware CPU> on cpulist0
cpu1: Nominal frequency 2000Mhz
cpu2: <Open Firmware CPU> on cpulist0
cpu2: Nominal frequency 2000Mhz
cpu3: <Open Firmware CPU> on cpulist0
cpu3: Nominal frequency 2000Mhz
cpu4: <Open Firmware CPU> on cpulist0
cpu4: Nominal frequency 2000Mhz
cpu5: <Open Firmware CPU> on cpulist0
cpu5: Nominal frequency 2000Mhz
cpu6: <Open Firmware CPU> on cpulist0
cpu6: Nominal frequency 2000Mhz
cpu7: <Open Firmware CPU> on cpulist0
cpu7: Nominal frequency 2000Mhz
cpu8: <Open Firmware CPU> on cpulist0
cpu8: Nominal frequency 2000Mhz
cpu9: <Open Firmware CPU> on cpulist0
cpu9: Nominal frequency 2000Mhz
cpu10: <Open Firmware CPU> on cpulist0
cpu10: Nominal frequency 2000Mhz
cpu11: <Open Firmware CPU> on cpulist0
cpu11: Nominal frequency 2000Mhz
cpu12: <Open Firmware CPU> on cpulist0
cpu12: Nominal frequency 2000Mhz
cpu13: <Open Firmware CPU> on cpulist0
cpu13: Nominal frequency 2000Mhz
cpu14: <Open Firmware CPU> on cpulist0
cpu14: Nominal frequency 2000Mhz
cpu15: <Open Firmware CPU> on cpulist0
cpu15: Nominal frequency 2000Mhz
pmu0: <Performance Monitoring Unit> irq 5 on ofwbus0
ofwbus0: <memory-controller@1080000> mem 0x1080000-0x1080fff irq 6 compat fsl,qoriq-memory-controller (no driver attached)
ofwbus0: <memory-controller@1090000> mem 0x1090000-0x1090fff irq 7 compat fsl,qoriq-memory-controller (no driver attached)
simplebus0: <crypto@8000000> mem 0x8000000-0x80fffff irq 8 compat fsl,sec-v5.0 (no driver attached)
syscon_generic_dev0: <syscon> mem 0x1e00000-0x1e0ffff on simplebus0
soctherm0: <QorIQ temperature sensors> mem 0x1f80000-0x1f8ffff irq 9 on simplebus0
i2c0: <Vybrid Family Inter-Integrated Circuit (I2C)> mem 0x2000000-0x200ffff irq 10 on simplebus0
iicbus0: <OFW I2C bus> on i2c0
iic0: <I2C generic I/O> on iicbus0
iicmux0: <PCA9547 IIC bus multiplexor> at addr 0xee on iicbus0
iicbus1: <OFW I2C bus> on iicmux0
iic1: <I2C generic I/O> on iicbus1
icee0: <AT24C512> at addr 0xa0 on iicbus1
icee0: size: 65536 bytes, addressing: 16-bits
iicbus1: <unknown card> at addr 0xa2
iicbus1: <unknown card> at addr 0xa6
icee1: <AT24C02> at addr 0xae on iicbus1
icee1: size: 256 bytes, addressing: 8-bits
iicbus2: <OFW I2C bus> on iicmux0
iic2: <I2C generic I/O> on iicbus2
iicbus2: <unknown card> at addr 0x30
iicbus3: <OFW I2C bus> on iicmux0
iic3: <I2C generic I/O> on iicbus3
iicbus3: <unknown card> at addr 0xb8
iicbus4: <OFW I2C bus> on iicmux0
iic4: <I2C generic I/O> on iicbus4
iicbus4: <unknown card> at addr 0x90
simplebus0: <i2c@2010000> mem 0x2010000-0x201ffff irq 11 disabled compat fsl,vf610-i2c (no driver attached)
i2c1: <Vybrid Family Inter-Integrated Circuit (I2C)> mem 0x2020000-0x202ffff irq 12 on simplebus0
iicbus5: <OFW I2C bus> on i2c1
iic5: <I2C generic I/O> on iicbus5
simplebus0: <i2c@2030000> mem 0x2030000-0x203ffff irq 13 disabled compat fsl,vf610-i2c (no driver attached)
i2c2: <Vybrid Family Inter-Integrated Circuit (I2C)> mem 0x2040000-0x204ffff irq 14 on simplebus0
iicbus6: <OFW I2C bus> on i2c2
iic6: <I2C generic I/O> on iicbus6
nxprtc0: <NXP PCF2129 RTC> at addr 0xa2 irq 138 on iicbus6
simplebus0: <i2c@2050000> mem 0x2050000-0x205ffff irq 15 disabled compat fsl,vf610-i2c (no driver attached)
simplebus0: <i2c@2060000> mem 0x2060000-0x206ffff irq 16 disabled compat fsl,vf610-i2c (no driver attached)
simplebus0: <i2c@2070000> mem 0x2070000-0x207ffff irq 17 disabled compat fsl,vf610-i2c (no driver attached)
simplebus0: <spi@20c0000> mem 0x20c0000-0x20cffff,0x20000000-0x2fffffff irq 18 compat nxp,lx2160a-fspi (no driver attached)
simplebus0: <spi@2100000> mem 0x2100000-0x210ffff irq 19 disabled compat fsl,lx2160a-dspi (no driver attached)
simplebus0: <spi@2110000> mem 0x2110000-0x211ffff irq 20 disabled compat fsl,lx2160a-dspi (no driver attached)
simplebus0: <spi@2120000> mem 0x2120000-0x212ffff irq 21 disabled compat fsl,lx2160a-dspi (no driver attached)
sdhci_fsl_fdt0: <NXP QorIQ Layerscape eSDHC controller> mem 0x2140000-0x214ffff irq 22 on simplebus0
sdhci_fsl_fdt0-slot0: Hardware doesn't specify timeout clock frequency, setting BROKEN_TIMEOUT quirk.
sdhci_fsl_fdt0-slot0: 700MHz HS 4bits VDD: 3.3V VCCQ: 3.3V 1.8V DRV: B DMA removable
sdhci_fsl_fdt0-slot0: ============== REGISTER DUMP ==============
sdhci_fsl_fdt0-slot0: Sys addr: 0xf6b28200 | Version:  0x00002202
sdhci_fsl_fdt0-slot0: Blk size: 0x00000200 | Blk cnt:  0x00000001
sdhci_fsl_fdt0-slot0: Argument: 0x04004000 | Trn mode: 0x00000000
sdhci_fsl_fdt0-slot0: Present:  0x01fd0000 | Host ctl: 0x00000002
sdhci_fsl_fdt0-slot0: Power:    0x0000000d | Blk gap:  0x00000000
sdhci_fsl_fdt0-slot0: Wake-up:  0x00000000 | Clock:    0x00000003
sdhci_fsl_fdt0-slot0: Timeout:  0x0000000b | Int stat: 0x00000000
sdhci_fsl_fdt0-slot0: Int enab: 0x377f11cf | Sig enab: 0x00000000
sdhci_fsl_fdt0-slot0: AC12 err: 0x00000000 | Host ctl2:0x00000000
sdhci_fsl_fdt0-slot0: Caps:     0x35f20000 | Caps2:    0x0000af07
sdhci_fsl_fdt0-slot0: Max curr: 0x00000000 | ADMA err: 0x00000000
sdhci_fsl_fdt0-slot0: ADMA addr:0x00000000 | Slot int: 0x00000000
sdhci_fsl_fdt0-slot0: ===========================================
sdhci_fsl_fdt0-slot0: Card inserted
mmc0: <MMC/SD bus> on sdhci_fsl_fdt0
sdhci_fsl_fdt1: <NXP QorIQ Layerscape eSDHC controller> mem 0x2150000-0x215ffff irq 23 on simplebus0
sdhci_fsl_fdt1-slot0: Hardware doesn't specify timeout clock frequency, setting BROKEN_TIMEOUT quirk.
sdhci_fsl_fdt1-slot0: 700MHz HS 8bits VDD: 3.3V VCCQ: 3.3V 1.8V DRV: B DMA removable
sdhci_fsl_fdt1-slot0: ============== REGISTER DUMP ==============
sdhci_fsl_fdt1-slot0: Sys addr: 0xf6b28200 | Version:  0x00002202
sdhci_fsl_fdt1-slot0: Blk size: 0x00000200 | Blk cnt:  0x00000001
sdhci_fsl_fdt1-slot0: Argument: 0x00020020 | Trn mode: 0x00000000
sdhci_fsl_fdt1-slot0: Present:  0x01f80000 | Host ctl: 0x00000002
sdhci_fsl_fdt1-slot0: Power:    0x0000000d | Blk gap:  0x00000000
sdhci_fsl_fdt1-slot0: Wake-up:  0x00000000 | Clock:    0x00000003
sdhci_fsl_fdt1-slot0: Timeout:  0x0000000c | Int stat: 0x00000000
sdhci_fsl_fdt1-slot0: Int enab: 0x377f11cf | Sig enab: 0x00000000
sdhci_fsl_fdt1-slot0: AC12 err: 0x00000000 | Host ctl2:0x00000000
sdhci_fsl_fdt1-slot0: Caps:     0x34f20000 | Caps2:    0x0000af07
sdhci_fsl_fdt1-slot0: Max curr: 0x00000000 | ADMA err: 0x00000000
sdhci_fsl_fdt1-slot0: ADMA addr:0x00000000 | Slot int: 0x00000000
sdhci_fsl_fdt1-slot0: ===========================================
uart0: <PrimeCell UART (PL011)> mem 0x21c0000-0x21c0fff irq 24 on simplebus0
uart0: console (115200,n,8,1)
uart0: fast interrupt
uart0: PPS capture mode: DCD
uart1: <PrimeCell UART (PL011)> mem 0x21d0000-0x21d0fff irq 25 on simplebus0
uart1: fast interrupt
uart1: PPS capture mode: DCD
simplebus0: <serial@21e0000> mem 0x21e0000-0x21e0fff irq 26 disabled compat arm,sbsa-uart (no driver attached)
simplebus0: <serial@21f0000> mem 0x21f0000-0x21f0fff irq 27 disabled compat arm,sbsa-uart (no driver attached)
gpioc0: <GPIO controller> on gpio0
gpioc1: <GPIO controller> on gpio1
gpioc2: <GPIO controller> on gpio2
gpioc3: <GPIO controller> on gpio3
simplebus0: <watchdog@23a0000> mem 0x23a0000-0x23a0fff,0x2390000-0x2390fff irq 32 compat arm,sbsa-gwdt (no driver attached)
simplebus0: <power-controller@1e34040> mem 0x1e34040-0x1e3405b compat fsl,lx2160a-rcpm (no driver attached)
simplebus0: <timer@2800000> mem 0x2800000-0x280ffff irq 33 compat fsl,lx2160a-ftm-alarm (no driver attached)
xhci0: <Synopsys Designware DWC3> mem 0x3100000-0x310ffff irq 34 on simplebus0
xhci0: snps id: 5533290a
xhci0: 64 bytes context size, 32-bit DMA
usbus0: trying to attach
usbus0 on xhci0
xhci0: usbpf: Attached
xhci1: <Synopsys Designware DWC3> mem 0x3110000-0x311ffff irq 35 on simplebus0
xhci1: snps id: 5533290a
xhci1: 64 bytes context size, 32-bit DMA
usbus1: trying to attach
usbus1 on xhci1
xhci1: usbpf: Attached
ahci0: <NXP QorIQ Layerscape AHCI controller> mem 0x3200000-0x320ffff,0x700100520-0x700100523 irq 36 on simplebus0
ahci0: AHCI v1.31 with 1 6Gbps ports, Port Multiplier not supported with FBS
ahci0: quirks=0x2<NOPMP>
ahci0: Caps: 64bit NCQ SNTF ALP CLO 6Gbps FBS PMD SSC PSC 32cmd CCC 1ports
ahci0: Caps2: SDS APST
ahcich0: <AHCI channel> at channel 0 on ahci0
ahcich0: Caps: FBSCP DSP
ahci1: <NXP QorIQ Layerscape AHCI controller> mem 0x3210000-0x321ffff,0x700100520-0x700100523 irq 37 on simplebus0
ahci1: AHCI v1.31 with 1 6Gbps ports, Port Multiplier not supported with FBS
ahci1: quirks=0x2<NOPMP>
ahci1: Caps: 64bit NCQ SNTF ALP CLO 6Gbps FBS PMD SSC PSC 32cmd CCC 1ports
ahci1: Caps2: SDS APST
ahcich1: <AHCI channel> at channel 0 on ahci1
ahcich1: Caps: FBSCP DSP
ahci2: <NXP QorIQ Layerscape AHCI controller> mem 0x3220000-0x322ffff,0x700100520-0x700100523 irq 38 on simplebus0
ahci2: AHCI v1.31 with 1 6Gbps ports, Port Multiplier not supported with FBS
ahci2: quirks=0x2<NOPMP>
ahci2: Caps: 64bit NCQ SNTF ALP CLO 6Gbps FBS PMD SSC PSC 32cmd CCC 1ports
ahci2: Caps2: SDS APST
ahcich2: <AHCI channel> at channel 0 on ahci2
ahcich2: Caps: FBSCP DSP
ahci3: <NXP QorIQ Layerscape AHCI controller> mem 0x3230000-0x323ffff,0x700100520-0x700100523 irq 39 on simplebus0
ahci3: AHCI v1.31 with 1 6Gbps ports, Port Multiplier not supported with FBS
ahci3: quirks=0x2<NOPMP>
ahci3: Caps: 64bit NCQ SNTF ALP CLO 6Gbps FBS PMD SSC PSC 32cmd CCC 1ports
ahci3: Caps2: SDS APST
ahcich3: <AHCI channel> at channel 0 on ahci3
ahcich3: Caps: FBSCP DSP
simplebus0: <pcie@3400000> mem 0x3400000-0x34fffff,0x8000000000-0x8000001fff irq 40,41,42 disabled type pci compat fsl,lx2160a-pcie (no driver attached)
simplebus0: <pcie@3500000> mem 0x3500000-0x35fffff,0x8800000000-0x8800001fff irq 43,44,45 disabled type pci compat fsl,lx2160a-pcie (no driver attached)
simplebus0: <pcie@3600000> mem 0x3600000-0x36fffff,0x9000000000-0x9000001fff irq 46,47,48 disabled type pci compat fsl,lx2160a-pcie (no driver attached)
simplebus0: <pcie@3700000> mem 0x3700000-0x37fffff,0x9800000000-0x9800001fff irq 49,50,51 disabled type pci compat fsl,lx2160a-pcie (no driver attached)
simplebus0: <pcie@3800000> mem 0x3800000-0x38fffff,0xa000000000-0xa000001fff irq 52,53,54 disabled type pci compat fsl,lx2160a-pcie (no driver attached)
simplebus0: <pcie@3900000> mem 0x3900000-0x39fffff,0xa800000000-0xa800001fff irq 55,56,57 disabled type pci compat fsl,lx2160a-pcie (no driver attached)
simplebus0: <iommu@5000000> mem 0x5000000-0x57fffff irq 58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114,115,116,117,118,119,120,121,122,123,124,125,126,127,128,129,130,131,132,133,134,135 compat arm,mmu-500 (no driver attached)
simplebus0: <console@8340020> mem 0x8340020-0x8340021 compat fsl,dpaa2-console (no driver attached)
simplebus0: <ptp-timer@8b95000> mem 0x8b95000-0x8b950ff compat fsl,dpaa2-ptp (no driver attached)
simplebus0: <mdio@8b96000> mem 0x8b96000-0x8b96fff irq 136 compat fsl,fman-memac-mdio (no driver attached)
simplebus0: <mdio@8b97000> mem 0x8b97000-0x8b97fff irq 137 compat fsl,fman-memac-mdio (no driver attached)
simplebus0: <fsl-mc@80c000000> mem 0x80c000000-0x80c00003f,0x8340000-0x837ffff compat fsl,qoriq-mc (no driver attached)
crypto: assign cryptosoft0 driver id 0, flags 0x6000000
armv8crypto0: <AES-CBC,AES-XTS,AES-GCM>
crypto: assign armv8crypto0 driver id 1, flags 0xe000000
Found SMCCC version 1.1
Device configuration finished.
procfs registered
Timecounters tick every 1.000 msec
lo0: bpf attached
vlan: initialized, using hash tables with chaining
tcp_init: net.inet.tcp.tcbhashsize auto tuned to 524288
IPsec: Initialized Security Association Processing.
usbus0: 5.0Gbps Super Speed USB v3.0
usbus1: 5.0Gbps Super Speed USB v3.0
ahcich0: AHCI reset...
ugen1.1: <Synopsys XHCI root HUB> at usbus1
uhub0 on usbus1
uhub0: <Synopsys XHCI root HUB, class 9/0, rev 3.00/1.00, addr 1> on usbus1
ugen0.1: <Synopsys XHCI root HUB> at usbus0
uhub1 on usbus0
uhub1: <Synopsys XHCI root HUB, class 9/0, rev 3.00/1.00, addr 1> on usbus0
ahcich0: SATA connect timeout time=10000us status=00000000
ahcich0: AHCI reset: device not found
ahcich1: AHCI reset...
ahcich1: SATA connect timeout time=10000us status=00000000
ahcich1: AHCI reset: device not found
ahcich2: AHCI reset...
ahcich2: SATA connect timeout time=10000us status=00000000
ahcich2: AHCI reset: device not found
ahcich3: AHCI reset...
ahcich3: SATA connect time=100us status=00000133
ahcich3: AHCI reset: device found
ahcich3: AHCI reset: device ready after 0ms
nxprtc0: registered as a time-of-day clock, resolution 0.015625s
sdhci_fsl_fdt0: Powering up sd/mmc
sdhci_fsl_fdt0-slot0: Divider 875 for freq 400000 (base 700000000)
mmc0: Probing bus
mmc0: SD probe: OK (OCR: 0x00ff8000)
mmc0: Current OCR: 0x00ff8000
mmc0: CMD8 failed, RESULT: 1
uhub0: 2 ports with 2 removable, self powered
uhub1: 2 ports with 2 removable, self powered
mmc0: Probing cards
mmc0: New card detected (CID 02544d53443031472895b5f490007300)
mmc0: New card detected (CSD 002d00321b5983d67efbff8016400000)
mmc0: Card at relative address 0xff85 added:
mmc0:  card: SD SD01G 2.8 SN 95B5F490 MFG 03/2007 by 2 TM
mmc0:  quirks: 0
mmc0:  bus: 4bit, 25MHz (normal speed timing)
mmc0:  memory: 2012160 blocks, erase sector 128 blocks
mmc0: setting transfer rate to 25.000MHz (normal speed timing)
sdhci_fsl_fdt0-slot0: Divider 14 for freq 25000000 (base 700000000)
mmcsd0: 1GB <SD SD01G 2.8 SN 95B5F490 MFG 03/2007 by 2 TM> at mmc0 25.0MHz/4bit/1024-block
Release APs...gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: Start searching for Re-Distributor
gic0: CPU11 Re-Distributor has been found
gic0: CPU5 Re-Distributor has been found
gic0: CPU6 Re-Distributor has been found
gic0: CPU11 Re-Distributor woke up
gic0: CPU9 Re-Distributor has been found
gic0: CPU6 Re-Distributor woke up
gic0: CPU3 Re-Distributor has been found
gic0: CPU11 enabled CPU interface via system registers
gic0: CPU10 Re-Distributor has been found
gic0: CPU6 enabled CPU interface via system registers
gic0: CPU13 Re-Distributor has been found
gic0: CPU2 Re-Distributor has been found
gic0: CPU3 Re-Distributor woke up
gic0: CPU12 Re-Distributor has been found
gic0: CPU5 Re-Distributor woke up
gic0: CPU1 Re-Distributor has been found
gic0: CPU4 Re-Distributor has been found
gic0: CPU7 Re-Distributor has been found
gic0: CPU5 enabled CPU interface via system registers
gic0: CPU9 Re-Distributor woke up
gic0: CPU3 enabled CPU interface via system registers
gic0: CPU1 Re-Distributor woke up
gic0: CPU7 Re-Distributor woke up
gic0: CPU10 Re-Distributor woke up
gic0: CPU1 enabled CPU interface via system registers
gic0: CPU14 Re-Distributor has been found
gic0: CPU15 Re-Distributor has been found
gic0: CPU9 enabled CPU interface via system registers
gic0: CPU13 Re-Distributor woke up
gic0: CPU8 Re-Distributor has been found
gic0: CPU2 Re-Distributor woke up
gic0: CPU4 Re-Distributor woke up
gic0: CPU7 enabled CPU interface via system registers
gic0: CPU8 Re-Distributor woke up
gic0: CPU14 Re-Distributor woke up
gic0: CPU10 enabled CPU interface via system registers
gic0: CPU15 Re-Distributor woke up
gic0: CPU8 enabled CPU interface via system registers
gic0: CPU4 enabled CPU interface via system registers
gic0: CPU2 enabled CPU interface via system registers
gic0: CPU12 Re-Distributor woke up
gic0: CPU13 enabled CPU interface via system registers
gic0: CPU12 enabled CPU interface via system registers
gic0: CPU14 enabled CPU interface via system registers
gic0: CPU15 enabled CPU interface via system registers
done
Trying to mount root from ufs:/dev/ufs/FreeBSD_Install [ro,noatime]...
GEOM: new disk mmcsd0
CPU  0: ARM Cortex-A72 r0p3 affinity:  0  0
pass0 at ahcich3 bus 0 scbus3 target 0 lun 0
mmc0: setting bus width to 4 bits normal speed timing
pass0:                    Cache Type = <64 byte D-cacheline,64 byte I-cacheline,PIPT ICache,64 byte ERG,64 byte CWG>
<KINGSTON SUV400S37120G 0C3J96R9> ACS-4 ATA SATA 3.x device
mmc0: Failed to set VCCQ for card at relative address 65413
pass0: Serial Number 50026B767B00EDF0
 Instruction Set Attributes 0 = <CRC32,SHA2,SHA1,AES+PMULL>
pass0: 600.000MB/s transfers Instruction Set Attributes 1 = <>
 (         Processor Features 0 = <GIC,AdvSIMD,FP,EL3 32,EL2 32,EL1 32,EL0 32>
SATA 3.x,          Processor Features 1 = <>
      Memory Model Features 0 = <TGran4,TGran64,SNSMem,BigEnd,16bit ASID,16TB PA>
      Memory Model Features 1 = <8bit VMID>
UDMA6, PIO 8192bytes      Memory Model Features 2 = <32bit CCIDX,48bit VA>
)
pass0: Command Queueing enabled
             Debug Features 0 = <2 CTX BKPTs,4 Watchpoints,6 Breakpoints,PMUv3,Debugv8>
ada0 at ahcich3 bus 0 scbus3 target 0 lun 0
ada0: <KINGSTON SUV400S37120G 0C3J96R9> ACS-4 ATA SATA 3.x device
ada0: Serial Number 50026B767B00EDF0
ada0: 600.000MB/s transfers (SATA 3.x, UDMA6, PIO 8192bytes)
ada0: Command Queueing enabled
ada0: 114473MB (234441648 512 byte sectors)
GEOM: new disk ada0
             Debug Features 1 = <>
         Auxiliary Features 0 = <>
         Auxiliary Features 1 = <>
CPU  1: ARM Cortex-A72 r0p3 affinity:  0  1
CPU  2: ARM Cortex-A72 r0p3 affinity:  1  0
CPU  3: ARM Cortex-A72 r0p3 affinity:  1  1
CPU  4: ARM Cortex-A72 r0p3 affinity:  2  0
CPU  5: ARM Cortex-A72 r0p3 affinity:  2  1
CPU  6: ARM Cortex-A72 r0p3 affinity:  3  0
CPU  7: ARM Cortex-A72 r0p3 affinity:  3  1
CPU  8: ARM Cortex-A72 r0p3 affinity:  4  0
CPU  9: ARM Cortex-A72 r0p3 affinity:  4  1
CPU 10: ARM Cortex-A72 r0p3 affinity:  5  0
CPU 11: ARM Cortex-A72 r0p3 affinity:  5  1
CPU 12: ARM Cortex-A72 r0p3 affinity:  6  0
CPU 13: ARM Cortex-A72 r0p3 affinity:  6  1
Root mount waiting for:CPU 14: ARM Cortex-A72 r0p3 affinity:  7  0
 usbus1CPU 15: ARM Cortex-A72 r0p3 affinity:  7  1

KTLS: Initialized 16 threads
WARNING: WITNESS option enabled, expect reduced performance.
regulator: shutting down unused regulators
ugen1.2: <vendor 0x04b4 product 0x6502> at usbus1
uhub2 on uhub0
uhub2: <vendor 0x04b4 product 0x6502, class 9/0, rev 2.10/50.10, addr 1> on usbus1
uhub2: MTT enabled
uhub2: 4 ports with 4 removable, self powered
Root mount waiting for: usbus1
ugen1.3: <SMI Corporation USB DISK> at usbus1
umass0 on uhub2
umass0: <SMI Corporation USB DISK, class 0/0, rev 2.00/11.00, addr 2> on usbus1
umass0:  SCSI over Bulk-Only; quirks = 0x4000
umass0:4:0: Attached to scbus4
GEOM: new disk da0
pass1 at umass-sim0 bus 0 scbus4 target 0 lun 0
pass1: <SMI USB DISK 1100> Removable Direct Access SPC-2 SCSI device
pass1: 40.000MB/s transfers
da0 at umass-sim0 bus 0 scbus4 target 0 lun 0
da0: <SMI USB DISK 1100> Removable Direct Access SPC-2 SCSI device
da0: 40.000MB/s transfers
da0: 7800MB (15974400 512 byte sectors)
da0: quirks=0x3<NO_SYNC_CACHE,NO_6_BYTE>
da0: Delete methods: <NONE(*),ZERO>
(da0:umass-sim0:0:0:0): PREVENT ALLOW MEDIUM REMOVAL not supported.
GEOM: da0: the secondary GPT header is not in the last LBA.
ugen1.4: <vendor 0x0424 product 0x2514> at usbus1
uhub3 on uhub2
uhub3: <vendor 0x0424 product 0x2514, class 9/0, rev 2.00/b.b3, addr 3> on usbus1
uhub3: MTT enabled
uhub3: 4 ports with 3 removable, self powered
ugen1.5: <vendor 0x04b4 product 0x6500> at usbus1
uhub4 on uhub0
uhub4: <vendor 0x04b4 product 0x6500, class 9/0, rev 3.00/50.10, addr 4> on usbus1
Root mount waiting for: usbus1
uhub4: 4 ports with 4 removable, self powered
mountroot: waiting for device /dev/ufs/FreeBSD_Install...
random: unblocking device.
nxprtc0: providing initial system time
start_init: trying /sbin/init
lo0: link state changed to UP

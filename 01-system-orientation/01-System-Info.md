**fastfetch**
..............                                      kali@kali
            ..,;:ccc,.                              ---------                
          ......''';lxO.                            OS: Kali GNU/Linux Rolli4
.....''''..........,:ld;                            Kernel: Linux 6.19.14+ka4
           .';;;:::;,,.x,                           Uptime: 2 mins           
      ..'''.            0Xxoc:,.  ...               Packages: 2981 (dpkg)    
  ....                ,ONkc;,;cokOdc',.             Shell: zsh 5.9           
 .                   OMo           ':ddo.           Display (Virtual-1): 128z
                    dMc               :OO;          DE: Xfce4 4.20           
                    0M.                 .:o.        WM: Xfwm4 (X11)          
                    ;Wd                             WM Theme: Kali-Dark      
                     ;XO,                           Theme: Fusion [Qt], Kali]
                       ,d0Odlc;,..                  Icons: Flat-Remix-Blue-D]
                           ..',;:cdOOd::,.          Font: Cantarell (11pt) []
                                    .:d;.':;.       Cursor: Adwaita (24px)   
                                       'd,  .'      Terminal: qterminal 2.3.0
                                         ;l   ..    Terminal Font: FiraCode )
                                          .o        CPU: Virtualized Apple Sn
                                            c       GPU: VMware SVGA II Adap)
                                            .'      Memory: 1.59 GiB / 10.83)
                                             .      Swap: 0 B / 3.10 GiB (0%)
                                                    Disk (/): 25.73 GiB / 544
                                                    Local IP (eth0): 10.0.2.4
                                                    Locale: en_US.UTF-8

                                                                            
                                                                            
                                                                             
┌──(kali㉿kali)-[~]
└─$ **inxi -Fxz**   
System:
  Kernel: 6.19.14+kali-arm64 arch: aarch64 bits: 64 compiler: gcc v: 15.2.0
  Desktop: Xfce v: 4.20.2 Distro: Kali GNU/Linux 2026.1 kali-rolling
    base: Debian testing
Machine:
  Message: No machine data: try newer kernel. Is dmidecode installed? Try
    -M --dmidecode.
CPU:
  Info: single core model: N/A bits: 64 type: UP smt: disabled arch: ARMv8
    rev: 0
  Speed: N/A min/max: N/A core: No per core speed data found.
    bogomips: N/A
  Features: Use -f option to see features
Graphics:
  Device-1: VMware SVGA II Adapter driver: vmwgfx v: 2.21.0.0
    bus-ID: 00:00.0
  Display: x11 server: X.Org v: 21.1.21 driver: X: loaded: modesetting
    unloaded: fbdev dri: swrast gpu: vmwgfx resolution: N/A
  API: EGL v: 1.5 drivers: kms_swrast,swrast platforms:
    active: gbm,x11,surfaceless,device inactive: wayland,device-0
  API: OpenGL v: 4.5 vendor: mesa v: 26.0.4-1 glx-v: 1.4
    direct-render: yes renderer: llvmpipe (LLVM 21.1.8 128 bits)
  Info: Tools: api: eglinfo,glxinfo de: xfce4-display-settings
    x11: xdriinfo, xdpyinfo, xprop, xrandr
Audio:
  Device-1: Intel 82801FB/FBM/FR/FW/FRW High Definition Audio
    vendor: SigmaTel driver: snd_hda_intel v: kernel bus-ID: 00:02.0
  API: ALSA v: k6.19.14+kali-arm64 status: kernel-api
  Server-1: PipeWire v: 1.6.4 status: active
Network:
  Device-1: Intel 82540EM Gigabit Ethernet driver: e1000 v: kernel
    port: 1020 bus-ID: 00:08.0
  IF: eth0 state: up speed: 1000 Mbps duplex: full mac: <filter>
  IF-ID-1: br-3f03f12e75d1 state: up speed: 10000 Mbps duplex: unknown
    mac: <filter>
  IF-ID-2: docker0 state: down mac: <filter>
  IF-ID-3: veth0486d8b state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-4: veth22ac78c state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-5: veth4f8ce36 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-6: veth501ee97 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-7: veth56e07cf state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-8: veth5ea1537 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-9: veth6e66b83 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-10: veth7c9f352 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-11: veth99010cf state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-12: veth9fe5f22 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-13: vethb3f5f47 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-14: vethca4e25e state: up speed: 10000 Mbps duplex: full
    mac: <filter>
  IF-ID-15: vethf51ed06 state: up speed: 10000 Mbps duplex: full
    mac: <filter>
Drives:
  Local Storage: total: 60.09 GiB used: 25.73 GiB (42.8%)
  ID-1: /dev/sda model: HARDDISK size: 60.09 GiB
Partition:
  ID-1: / size: 54.83 GiB used: 25.73 GiB (46.9%) fs: ext4 dev: /dev/sda3
  ID-2: /boot/efi size: 976.7 MiB used: 368 KiB (0.0%) fs: vfat
    dev: /dev/sda2
Swap:
  ID-1: swap-1 type: partition size: 3.1 GiB used: 0 KiB (0.0%)
    dev: /dev/sda4
Sensors:
  Src: lm-sensors+/sys Message: No sensor data found using
    /sys/class/hwmon or lm-sensors.
Info:
  Memory: total: 12 GiB note: est. available: 10.83 GiB
    used: 1.64 GiB (15.1%)
  Processes: 228 Uptime: 2m Init: systemd
  Packages: 2985 Compilers: clang: 21.1.8 gcc: 15.2.0 Shell: Zsh v: 5.9
    inxi: 3.3.40

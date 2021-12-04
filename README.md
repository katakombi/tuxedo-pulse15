# tuxedo-pulse15

```
stefan@niteking:~$ inxi -F
System:
  Host: niteking Kernel: 5.11.0-40-generic x86_64 bits: 64 
  Desktop: Gnome 3.36.9 Distro: Ubuntu 20.04.3 LTS (Focal Fossa) 
Machine:
  Type: Laptop System: TUXEDO product: TUXEDO Pulse 15 Gen1 v: Standard 
  serial: <superuser/root required> 
  Mobo: TUXEDO model: PULSE1501 v: Standard 
  serial: <superuser/root required> UEFI: American Megatrends v: N.1.07.A02 
  date: 12/08/2020 
Battery:
  ID-1: BAT0 charge: 77.0 Wh condition: 91.6/91.6 Wh (100%) 
CPU:
  Topology: 8-Core model: AMD Ryzen 7 4800H with Radeon Graphics bits: 64 
  type: MT MCP L2 cache: 4096 KiB 
  Speed: 1397 MHz min/max: 1400/2900 MHz Core speeds (MHz): 1: 1397 2: 1347 
  3: 1397 4: 1397 5: 1397 6: 1397 7: 1397 8: 1397 9: 1397 10: 1397 11: 1400 
  12: 1397 13: 1397 14: 1397 15: 1397 16: 1397 
Graphics:
  Device-1: AMD Renoir driver: amdgpu v: kernel 
  Display: x11 server: X.Org 1.20.11 driver: amdgpu,ati 
  unloaded: fbdev,modesetting,vesa resolution: 1920x1080~60Hz 
  OpenGL: renderer: AMD RENOIR (DRM 3.40.0 5.11.0-40-generic LLVM 12.0.0) 
  v: 4.6 Mesa 21.0.3 
Audio:
  Device-1: AMD driver: snd_hda_intel 
  Device-2: AMD Raven/Raven2/FireFlight/Renoir Audio Processor driver: N/A 
  Device-3: AMD Family 17h HD Audio driver: snd_hda_intel 
  Sound Server: ALSA v: k5.11.0-40-generic 
Network:
  Device-1: Intel Wi-Fi 6 AX200 driver: iwlwifi 
  IF: wlp1s0 state: up mac: 78:2b:46:2b:07:c3 
  Device-2: Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet 
  driver: r8169 
  IF: eno1 state: down mac: b0:25:aa:3d:f9:ea 
Drives:
  Local Storage: total: 1.82 TiB used: 6.95 GiB (0.4%) 
  ID-1: /dev/sda vendor: Samsung model: SSD 860 EVO M.2 2TB size: 1.82 TiB 
Partition:
  ID-1: / size: 1.76 TiB used: 6.83 GiB (0.4%) fs: ext4 dev: /dev/dm-1 
  ID-2: /boot size: 975.9 MiB used: 122.5 MiB (12.6%) fs: ext3 
  dev: /dev/sda1 
  ID-3: swap-1 size: 8.00 GiB used: 0 KiB (0.0%) fs: swap dev: /dev/dm-2 
Sensors:
  System Temperatures: cpu: 28.1 C mobo: N/A gpu: amdgpu temp: 27 C 
  Fan Speeds (RPM): N/A 
Info:
  Processes: 363 Uptime: 7m Memory: 29.30 GiB used: 1.31 GiB (4.5%) 
  Shell: bash inxi: 3.0.38 

```
BOOT_IMAGE=/vmlinuz-5.11.0-40-generic root=/dev/mapper/system-root ro quiet splash xhci_hcd.quirks=1073741824 vt.handoff=7
```

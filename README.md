# thinkpad-x270-opencore

# Supported OS
- [x] macOS 13.1 (Ventura)

# Laptop's Hardware
- <b>Model</b>: Thinkpad X270 (20HMS00T00)
- <b>CPU</b>: Intel Core i5-7200U 2 x 2.5 - 3.1 GHz, Kaby Lake
- <b>GPU</b>: Intel HD Graphics 620
- <b>RAM</b>: 8 GB 2400MHz DDR4
- <b>Screen</b>: 12,5" (1920x1080)
- <b>Wi-Fi</b>: Intel Dual Band Wireless-AC 8265
- <b>Camera</b>: 720p
- <b>Battery</b>: 3-cell with inside battery 

# Bios settings

<b>Security</b>
- `Security Chip` **Disabled**
- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**
- `Anti-Theft -> Computrace -> Current Setting` **Disabled**
- `Secure Boot -> Secure Boot` **Disabled**
- `Intel SGX -> Intel SGX Control` **Disabled**
- `Device Guard` **Disabled**


<b>Startup</b>
- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**


# What's Working?
- [x] Intel HD 620 Graphics (incuding graphics acceleration)
- [x] CPU Power Management
- [x] Battery
- [x] All USB ports
- [x] HDMI port (including HDMI Audio)
- [x] Intel Ethernet port
- [x] Audio
- [x] Trackpad (gestures work but not the trackpad click. tap to click works.)
- [x] Shutdown / Reboot 
- [x] Keyboard (incuding all fn Keys)
- [x] Wi-Fi
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] Sleep / Wake (lid sleep and lid wake) (works for me you can try for yourself)


# What's not working? ⚠️
- [x] Internal camera (including Facetime)
- [x] Bluetooth (I will try to fix that)

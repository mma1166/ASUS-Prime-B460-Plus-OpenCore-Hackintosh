# PC Components

```
Board:    Asus Prime B460 Plus
CPU:      Intel® Core™ i7-10700 
VGA:      Intel UHD Graphics 630
RAM:      Corsair Vengeance RGB Pro 8GB DDR4 3200MHz Ram X2
SSD:      HP S700 250 GB SATA III SSD
PSU:      Corsair CV550 550W 80+ Bronze certified PSU 
```

#Hackintosh

# Mac OS Monterey  + OpenCore (0.7.7)

- https://dortania.github.io/OpenCore-Desktop-Guide

# Works

- Sleep
- Wake
- Audio
- Ethernet
- DisplayPort + HDMI
- All USB ports (Full 3.0 + 2.0)
# Not Working:
- Nothing

# Result

![Info](/images/Info1.png)

# Note

Please change MLB, SystemSerialNumber, SystemUUID as your desire.

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>xxxxxxxx</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac20,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```

# Hackintosh-Intel-i5-10600-iGPU-AsRock-B460M-Pro4

# Info PC

```
MB: AsRock B460M Pro4
CPU: Intel® Core™ i5-10600
VGA: Intel UHD Graphics 630
RAM: 24GB HyperX DDR4 16GB+8GB 3200Mhz FURY Black
SSD: Kingston A400 480GB SA400S37
Bluetooth: Asus USB-BT400
Case + PSU: Gamemax ET-211-450 450W Black
```

# Hackintosh + OpenCore (Supported version: 0.6.0)

- https://dortania.github.io/OpenCore-Desktop-Guide

# Works

- Sleep
- Wake
- Audio
- Ethernet
- Bluetooth
- DisplayPort + HDMI simultaneously
- All USB ports (Full 3.0 + 2.0 + type C)

# Result

![Info](/images/info.png)

Cinebench R20 Multi Core
![Cinebench](/images/cb-mc.png)

Cinebench R20 Single Core
![Cinebench](/images/cb-sc.png)

# Note

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>ESIzRFVm</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac19,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
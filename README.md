# Redmi Note 12 TWRP Recovery


## Steps to flash Recovery

1. Unzip TWRP Xiaomi Redmi Note 12 file
2. Extract Recovery image and Platform Tools
3. Copy recovery image into Platform Tools folder
4. Open command prompt in Platfrom Tools folder
5. Put phone into fastboot mode using Power Key + Volume Down Key
6. Execute following command

```#!/bin/sh
fastboot devices

fastboot flash recovery_a <recovery_img>

fastboot flash recovery_b <recovery_img>

exit
```

7. Reboot your device! Booom you have TWRP installed.

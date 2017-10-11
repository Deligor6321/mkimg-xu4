
```
Utility to create self-installer image to ODROID-XU4

Usage: mkimg-xu4 [-v|-f|-h] [all|sd|emmc|sd2emmc] UPDATE OUTPUT_DIR
    -v: Enable verbose output
    -f: Don't ask for confirmation of the image creation
    -h: Show this help
    all | sd | emmc | sd2emmc : The way you want to deploy image to the device
    UPDATE: The archive with built android images, e.g. ~/update.zip
    OUTPUT_DIR: The block device to write the image to, e.g. /dev/sdh

Example:
    mkimg-xu4 -vf all update.zip .
```


sam3x (cortex-m3) linux images
==================

Images for the sam3x (cortex-m3) linux kernel, ramdisk and bootloader

Program the bootloader_release.bin file to internal flash of the Sam3X at 0x80000. 
Set GPNVM to boot from Flash, and boot from flash block 0.

Copy Image and ramdisk to the root directory of the SD card to be inserted into the
SAM3X-EK dev kit.  e.g.  e:\Image and e:\ramdisk

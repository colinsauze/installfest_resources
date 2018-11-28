# Installing Linux on a Mac
 * More details https://www.maketecheasier.com/install-dual-boot-ubuntu-mac/
## Repartition
 * Repartition disk with Mac "Disk Utility" under "Applications/Utilities", leave Linux some empty space, don't make it a parition.
 ## Install reFind boot manager (MacOS)
 * This gives us a boot choice screen on startup to allow dual boot. Not needed if removing OSX.
 * Install reFind boot manager http://sourceforge.net/projects/refind/files/0.11.2/refind-bin-0.11.2.zip/download
  * Reboot into recover mode by pressing Command + R at startup. 
  * open a terminal and type "csrutil disable"
  * Reboot and install reFind
## Install Linux    
 * Boot up with USB drive inserted and hold down the Option key
 * Choose EFI boot
 * Normal Linux installer should start, repartition the free space to have Linux+swap partitions
 * If it boots straight to Linux, either reinstall reFind in Linux or follow instructions at https://www.rodsbooks.com/refind/bootcoup.html#efibootmgr

# Installing Linux on a Windows 8 System with UEFI
## Secure boot
* You shouldn't need to disable secure boot for most modern distros.
* https://www.appgeeker.com/recovery/disable-uefi-secure-boot-in-windows-8.html
* If you really do: hold down Shift key while selecting Restart. Go to Troubleshoot > Advanced Options: UEFI Firmware Settings.
## Installing Linux

# Installing Linux on a Windows 10 System with UEFI

# Installing Windows Subsystem for Linux


# wileyfox-kipper-cm-13.1.2
Restore Wileyfox Storm (Kipper)

fastboot flash aboot emmc_appsboot.mbn
fastboot flash abootbak emmc_appsboot.mbn
fastboot erase DDR
fastboot flash sbl1 sbl1.mbn
fastboot flash sbl1bak sbl1.mbn
fastboot flash tz tz.mbn
fastboot flash tzbak tz.mbn
fastboot flash hyp hyp.mbn
fastboot flash hypbak hyp.mbn
fastboot flash rpm rpm.mbn
fastboot flash rpmbak rpm.mbn
fastboot flash modem NON-HLOS.bin
fastboot flash cache cache.img
fastboot erase splash
fastboot flash splash splash.img
fastboot flash system system.img
fastboot flash recovery recovery.img
fastboot flash userdata userdata.img
fastboot flash boot boot.img

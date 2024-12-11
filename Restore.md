# wileyfox-kipper

## Restore Wileyfox Storm (Kipper)

fastboot flash aboot emmc_appsboot.mbn <br>
fastboot flash abootbak emmc_appsboot.mbn <br>
fastboot erase DDR <br>
fastboot flash sbl1 sbl1.mbn <br>
fastboot flash sbl1bak sbl1.mbn <br>
fastboot flash tz tz.mbn <br>
fastboot flash tzbak tz.mbn <br>
fastboot flash hyp hyp.mbn <br>
fastboot flash hypbak hyp.mbn <br>
fastboot flash rpm rpm.mbn <br>
fastboot flash rpmbak rpm.mbn <br>
fastboot flash modem NON-HLOS.bin <br>
fastboot flash cache cache.img <br>
fastboot erase splash <br>
fastboot flash splash splash.img <br>
fastboot flash system system.img <br>
fastboot flash recovery recovery.img <br>
fastboot flash userdata userdata.img <br>
fastboot flash boot boot.img <br> 

## Development for Nothing CMF Phone 1 "`Tetris`"

<div>
  <img align="right" width=35%" src="https://i.ibb.co/whvY2zLS/cmf-Phone1.png">
</div>

This organization contains all the important repositories required to build custom ROMs for Nothing CMF Phone 1

### Required device specific repositories
* [**Device tree**](https://github.com/CMF-Phone-1/android_device_nothing_Tetris) (`android_device_nothing_Tetris`)
* [**Device kernel tree (Compiled outputs from kernel source)**](https://github.com/CMF-Phone-1/android_device_nothing_Tetris-kernel) (`android_device_nothing_Tetris-kernel`)
* [**Vendor tree**](https://github.com/CMF-Phone-1/proprietary_vendor_nothing_Tetris) (`proprietary_vendor_nothing_Tetris`)

### Other required repositories
* [**MediaTek sepolicy**](https://github.com/LineageOS/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek hardware**](https://github.com/LineageOS/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**Hardware Dolby**](https://github.com/swiitch-OFF-Lab/hardware_dolby/tree/sony-A17) (`android_hardware_dolby`)
* [**Dolby UI**](https://github.com/swiitch-OFF-Lab/packages_apps_DolbyUI/tree/a) (`android_packages_apps_DolbyUI`)


### Required patches
* [**Add 60FPS recording on Aperture (1)**](https://github.com/CMF-Phone-1/platform_packages_apps_Aperture/commit/1c7dc37dd2721e5207d0eabe988b2c8acd8bf840) [**(2)**](https://github.com/CMF-Phone-1/platform_packages_apps_Aperture/commit/00e223c82aa4acf7d15a4e7b556897af19d4a1ff) (`android_packages_apps_Aperture`)
* [**Add dither logic for MTK udfps optical**](https://github.com/Nothing-2A/android_frameworks_native/commit/7b7807349f7b66c61444e32e4a26b025932117d8) (`android_frameworks_native`)
* [**SystemUI: Reverse MediaTek udfps dimlayer changes**](https://github.com/Nothing-2A/android_frameworks_base/commit/71955520858075bfeb8b52009151ba20401f27e3) (`android_frameworks_base`)

### fenrir patched LK support
* [**Allow booting with fenrir patched LKs**](https://github.com/CMF-Phone-1/android_system_fs_fs_mgr/commit/c02c41f0bdfc106ef260125361681076c9c01fee) (`android_system_fs_fs_mgr`)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/CMF-Phone-1/platform_system_core/commit/6beb2eaff61ae6d77e07e89629f819cd18feee49) (`android_system_core`)

### Device kernel repositories
* [**Kernel source**](https://github.com/CMF-Phone-1/android_kernel_6.1_nothing_mt6878) (`android_kernel_6.1_nothing_mt6878`)
* [**External kernel modules source**](https://github.com/CMF-Phone-1/android_kernel_modules_nothing_mt6878) (`android_kernel_modules_nothing_mt6878`)
* [**Device kernel modules source**](https://github.com/CMF-Phone-1/android_kernel_device_modules_6.1_nothing_mt6878) (`android_kernel_device_modules_6.1_nothing_mt6878`)


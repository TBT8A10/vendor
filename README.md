### Hardware & Blobs info
* **LCD (Display)**: ShenZhen Strong Photoelectric SQ080B331M-I7401
    * Resolution: 800x1280
    * Seems like it has some relation with the TV080WXM-NL0 LCD, so both schematics may be similar
* **WiFi & Bluetooth Chip**: Unisoc uwe5622
    * Firmware: /vendor/etc/firmware/wcnmodem.bin `W21.10.3`
* **GPU**: PowerVR Rogue G6110 (BVNC 5.9.1.46)
    * All blobs come from the Rockchip vendor
    * bin
        * pvrsrvctl `UM P 5.38`
        * pvrtld `UM Q 5.58`
    * firmware
        * rgx.fw.signed.5.9.1.46 `UM Q 5.56`
    * lib
        * egl
            * egl.cfg
            * libEGL_POWERVR_ROGUE.so `UM Q 5.56`
            * libGLESv1_CM_POWERVR_ROGUE.so `UM Q 5.56`
            * libGLESv2_POWERVR_ROGUE.so `UM Q 5.58`
        * hw
            * gralloc.rk3368.so `UM Q 5.58`
            * memtrack.rk3368.so `UM Q 5.56`
            * vulkan.rk3368.so `Available on rockchip vendor but not on this vendor`
        * modules
            * pvrsrvkm.ko `UM Q 5.58`
        * libGLESv2_POWERVR_ROGUE.so `Available on rockchip vendor but not on this vendor`
        * libIMGegl.so `UM Q 5.58`
        * libLLVMIMG.so `11/11/2016`
        * libPVROCL.so `UM Q 5.56`
        * libPVRScopeServices.so `UM Q 5.58`
        * libclangIMG.so `11/11/2016`
        * libcreatesurface.so `UM N 5.10`
        * libglslcompiler.so `UM Q 5.56`
        * liboclcompiler.so `UM N 5.10`
        * libpvrANDROID_WSEGL.so `UM Q 5.56`
        * libsrv_init.so `Available on rockchip vendor but not on this vendor`
        * libsrv_um.so `UM Q 5.58`
        * libufwriter.so `UM Q 5.56`
        * libusc.so `UM Q 5.56`
    * lib64 `Available on rockchip vendor but not on this vendor`
    * etc
        * powervr.ini

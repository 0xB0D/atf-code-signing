# atf-code-signing

This is a storage repositry for

- image_sign.sh
- bl2_sign.csf

Both files in conjunction are used to sign an Arm Trusted Firmware BL2.bin image
such that an i.MX7 WaRP7 board which has been set to secure boot mode will
authenticate and boot the supplied image.

More information can be found by reading the Arm Trusted Firmware WaARP7
https://github.com/ARM-software/arm-trusted-firmware/blob/master/docs/plat/warp7.rst

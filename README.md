# android_vendor_xiaomi_lisa-firmware

Firmware images for Xiaomi 11 Lite NE (lisa), to include in custom ROM builds.

**Current version**: fw_lisa_miui_LISAGlobal_V13.0.2.0.SKOMIXM_737bc75f14_12.0

### How to use?

1. Clone this repo to `vendor/xiaomi/lisa-firmware`

2. Include it from `BoardConfig.mk` in device tree:

```
# Firmware
-include vendor/xiaomi/lisa-firmware/BoardConfigVendor.mk
```

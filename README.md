# android_vendor_xiaomi_lisa-firmware

Firmware images for Xiaomi 11 Lite NE (lisa), to include in custom ROM builds.

**Current version**: fw_lisa_miui_LISA_V14.0.5.0.TKOCNXM_25171e94ec_13.0

### How to use?

1. Clone this repo to `vendor/xiaomi/lisa-firmware`

2. Include it from `BoardConfig.mk` in device tree:

```
# Firmware
-include vendor/xiaomi/lisa-firmware/BoardConfigVendor.mk
```

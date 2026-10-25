# Proprietary Prebuilts for Xiaomi Leica Camera (Miatoll)

Proprietary vendor blobs and prebuilts for Xiaomi Leica Camera v5.0 (Build Beta 7.3) and ExtraPhoto.
Designed for **Xiaomi Miatoll** (`curtana`, `gram`, `joyeuse`, `excalibur`).

> [!IMPORTANT]
> **Compatibility:** Specifically designed and built for **Android 16 and Android 17 (A16 / A17) ONLY**.

## Build Information
- **Version:** Leica Camera v5.0
- **Build Version:** Beta 7.3
- **Target OS:** Android 16 & Android 17 (A16 / A17 Only)
- **Camera Port & Builds:** [ℌ𝔞𝔪𝔦𝔡𝔬](https://github.com/Hamido)
- **Maintainer:** [Abdo Ahmed Elbanaa](https://github.com/AbdoAhmedElbanaa)

## Source Tree Location
```bash
vendor/xiaomi/leicacamera_miatoll
```

## Structure
- `Android.bp`: Soong blueprint defining prebuilt apps (`MiuiCamera`, `MiuiExtraPhoto`) and 64-bit camera JNI libraries.
- `BoardConfigVendor.mk`: Vendor board configuration.
- `leicacamera_miatoll-vendor.mk`: Vendor makefile defining product packages, internal native library copy rules, and system library symlinks.
- `proprietary/`: Extracted Leica Camera APKs, libraries, and sub-components.

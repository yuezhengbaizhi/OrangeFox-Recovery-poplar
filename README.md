# android_device_sony_poplar
Tree for building TWRP for Xperia XZ1
             By Sjll & Yuezhengbaizhi

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_maple-eng

mka adbd recoveryimage

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (4x2.45 GHz Kryo & 4x1.9 GHz Kryo)
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 4 GB RAM
Shipped Android Version | 7.1.1
Storage | 64 GB
Battery | Li-Po 3300 mAh battery
Display | 3840 x 2160 pixels, 5.5 inches (~870 ppi pixel density)
Rear Camera  | 17 MP Motion Eye | 960fps

Device configuration for Samsung Galaxy Prevail LTE (coreprimeltespr G360P)
==================================================

## NOTE
This project is a work in progress and still not functional.
Any contributions are welcome.

## Device Specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 1.2 GHz ARM® Cortex™ A53
CHIPSET | Qualcomm MSM8916 Snapdragon 410
GPU     | Adreno 306
Ram     | 1GB
Shipped Android Version | 4.4.4
Latest Android Version | 4.4.4
Storage | 8GB
Battery | 2000 mAh
Display | 480 x 800 pixels, 4.5" (~207 ppi pixel density)
Rear Camera  | 5 MP, f/2.6, autofocus, LED flash
Front Camera | 2 MP
Release Date | November 2014

## Instructions

Get Android 4.4.4_r1
```
$ mkdir android-4.4.4_r1_source
$ cd android-4.4.4_r1_source
$ repo init -u https://android.googlesource.com/platform/manifest -b android-4.4.4_r1
$ repo sync
```

Download ``coreprimeltespr.xml`` from [project](https://github.com/jjdicharry/android_local_manifest_coreprimeltespr) to ``android-4.4.4_r1_source/.repo/local_manifests``.

Then run:
```
$ repo sync
```

After running:
```
$ . build/envsetup.sh
```

You should have the new lunch combo: **aosp_coreprimeltespr-userdebug**


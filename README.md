TWRP Device Tree for Cubot DINOSAUR 
===========
Unoffical Build for MT6735 TWRP 
------------------

the way to do:
```
- repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-5.1

- repo sync

- git clone
  https://github.com/h0sch180/android_twrp_device_cubot_dinosaur device/CUBOT/DINOSAUR

- . build/envsetup.sh

- lunch omni_MAX-eng

- make -j# recoveryimage [# : no. of cpu core]
```


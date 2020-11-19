## Recovery Device Tree for the Samsung Galaxy S10 Lite (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_r5q-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_r5q

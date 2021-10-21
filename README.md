## Recovery Device Tree for the Samsung Galaxy A12 Nacho (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a12s-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_a12s

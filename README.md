# Skia MTK Patches
Patches for Skia to run correctly on MTK, fixes videocodecs too.

## Source commit (Allow to rebind GL texture if AHB content has changed)
https://github.com/phhusson/platform_external_skia/commit/291ef6981994f98173d6a6505aa89a018d7bedd3

## How to apply
`cd (path to directory with sources)/external/skia`  
`patch -p0 < (path to directory with a patches)/*.patch`

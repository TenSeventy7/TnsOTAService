+++
addonPublisher = "TenSeventy7"
category = ""
description = "Beta builds of Fresh Core."
imageUrl = "/uploads/slide26.PNG"
packageName = "io.tns.shadowx.upstream"
rom = "fresh"
title = "Fresh Core Beta"
versionNumber = 93
[addon]
noMirror = true
packageHash = "hash"
packageSize = 12337000
packageUrl = "https://github.com/TenSeventy7/android_kernel_samsung_exynos9610_fresh/releases/download/ci_97-upstream/FRSH_CORE_a50_upstream_1621203679.zip"
versionName = "ci_upstream-93"

+++
This addon is **not uninstallable** and cannot be removed unless Fresh is reinstalled. This addon **replaces** the stable build of Fresh Core installed with beta, upstream builds straight from the kernel repository.

**Builds may be unstable,** install at your own risk.

Fresh Core is the new kernel included with Fresh 3 that powers your device through your day. Optimized for balanced performance and battery, you can experience new features without sacrificing battery life.

**Additional features include:**

* Added additional CPU governors, 'schedutil' as default.
* Added additional I/O schedulers, 'anxiety' is set as default.
* Various kernel and performance improvements.
* Backported some changes from S10/Note10.
* Releases are compiled with @arter97's stable \[GCC 10.2.0\]
* Replaced kernel RNG (HWRandom) with SRandom.
* Magisk installed by default.
* State notifier support for various kernel drivers.
* Uses \`FLATMEM\` instead of \`SPARSEMEM\`.
* Disabled basic Samsung hardening (Knox, etc) by default.
* DriveDroid support
* WireGuard support
* Gentle Fair sleepers support
* Support for storages formatted with NTFS
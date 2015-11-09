Tegra baseline test results for 20151109130523_69585842e8a39449e0514d771abf9a63bd14d99c


Here are some basic Tegra test results for Linux 20151109130523_69585842e8a39449e0514d771abf9a63bd14d99c.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20151109130523_69585842e8a39449e0514d771abf9a63bd14d99c/20151109130523/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20151109130523_69585842e8a39449e0514d771abf9a63bd14d99c
Test-Serial: 20151109130523
Commit-ID: 69585842e8a39449e0514d771abf9a63bd14d99c
Test-Target-Board-Count: 5
Test-Boot-Count: 9

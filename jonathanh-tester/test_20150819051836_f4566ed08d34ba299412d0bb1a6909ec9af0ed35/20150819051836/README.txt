Tegra baseline test results for 20150819051836_f4566ed08d34ba299412d0bb1a6909ec9af0ed35


Here are some basic Tegra test results for Linux 20150819051836_f4566ed08d34ba299412d0bb1a6909ec9af0ed35.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20150819051836_f4566ed08d34ba299412d0bb1a6909ec9af0ed35/20150819051836/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150819051836_f4566ed08d34ba299412d0bb1a6909ec9af0ed35
Test-Serial: 20150819051836
Commit-ID: f4566ed08d34ba299412d0bb1a6909ec9af0ed35
Test-Target-Board-Count: 5
Test-Boot-Count: 9

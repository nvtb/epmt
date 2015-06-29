Tegra baseline test results for 20150319225643_e8444885428c4257999e632eff35e8e8c8a8b504


Here are some basic Tegra test results for Linux 20150319225643_e8444885428c4257999e632eff35e8e8c8a8b504.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150319225643_e8444885428c4257999e632eff35e8e8c8a8b504/20150319225643/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150319225643_e8444885428c4257999e632eff35e8e8c8a8b504
Test-Serial: 20150319225643
Commit-ID: e8444885428c4257999e632eff35e8e8c8a8b504
Test-Target-Board-Count: 5
Test-Boot-Count: 8

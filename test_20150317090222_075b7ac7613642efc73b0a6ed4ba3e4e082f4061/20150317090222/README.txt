Tegra baseline test results for 20150317090222_075b7ac7613642efc73b0a6ed4ba3e4e082f4061


Here are some basic Tegra test results for Linux 20150317090222_075b7ac7613642efc73b0a6ed4ba3e4e082f4061.
Logs and other details at:

    http://nvt.pwsan.com/pub/swarren-tester/testlogs/test_20150317090222_075b7ac7613642efc73b0a6ed4ba3e4e082f4061/20150317090222/


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
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_20150317090222_075b7ac7613642efc73b0a6ed4ba3e4e082f4061
Test-Serial: 20150317090222
Commit-ID: 075b7ac7613642efc73b0a6ed4ba3e4e082f4061
Test-Target-Board-Count: 4
Test-Boot-Count: 7

Tegra baseline test results for 20151125061657_bd4f203e433387d39be404b67ad02acf6f76b7bc


Here are some basic Tegra test results for Linux 20151125061657_bd4f203e433387d39be404b67ad02acf6f76b7bc.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20151125061657_bd4f203e433387d39be404b67ad02acf6f76b7bc/20151125061657/


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
Branch: test_20151125061657_bd4f203e433387d39be404b67ad02acf6f76b7bc
Test-Serial: 20151125061657
Commit-ID: bd4f203e433387d39be404b67ad02acf6f76b7bc
Test-Target-Board-Count: 5
Test-Boot-Count: 9

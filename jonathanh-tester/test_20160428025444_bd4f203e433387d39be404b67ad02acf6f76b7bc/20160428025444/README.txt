Tegra baseline test results for 20160428025444_bd4f203e433387d39be404b67ad02acf6f76b7bc


Here are some basic Tegra test results for Linux 20160428025444_bd4f203e433387d39be404b67ad02acf6f76b7bc.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20160428025444_bd4f203e433387d39be404b67ad02acf6f76b7bc/20160428025444/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    FAIL: ( 1/ 3): tegra210-p2371-0000
    Pass: ( 2/ 3): qemu-vexpress64, tegra132-norrin

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_20160428025444_bd4f203e433387d39be404b67ad02acf6f76b7bc
Test-Serial: 20160428025444
Commit-ID: bd4f203e433387d39be404b67ad02acf6f76b7bc
Test-Target-Board-Count: 5
Test-Boot-Count: 9

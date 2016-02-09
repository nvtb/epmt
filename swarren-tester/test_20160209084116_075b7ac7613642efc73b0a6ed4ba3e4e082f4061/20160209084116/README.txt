Tegra baseline test results for 20160209084116_075b7ac7613642efc73b0a6ed4ba3e4e082f4061


Here are some basic Tegra test results for Linux 20160209084116_075b7ac7613642efc73b0a6ed4ba3e4e082f4061.
Logs and other details at:

    https://nvtb.github.io//epmt/swarren-tester/test_20160209084116_075b7ac7613642efc73b0a6ed4ba3e4e082f4061/20160209084116/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra20-trimslice
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 4): tegra20-trimslice
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_20160209084116_075b7ac7613642efc73b0a6ed4ba3e4e082f4061
Test-Serial: 20160209084116
Commit-ID: 075b7ac7613642efc73b0a6ed4ba3e4e082f4061
Test-Target-Board-Count: 5
Test-Boot-Count: 9

Tegra baseline test results for 20170322150929_4f4f9722474101ee6ec17a60323591b2c51f5a0b


Here are some basic Tegra test results for Linux 20170322150929_4f4f9722474101ee6ec17a60323591b2c51f5a0b.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20170322150929_4f4f9722474101ee6ec17a60323591b2c51f5a0b/20170322150929/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_20170322150929_4f4f9722474101ee6ec17a60323591b2c51f5a0b
Test-Serial: 20170322150929
Commit-ID: 4f4f9722474101ee6ec17a60323591b2c51f5a0b
Test-Target-Board-Count: 9
Test-Boot-Count: 14

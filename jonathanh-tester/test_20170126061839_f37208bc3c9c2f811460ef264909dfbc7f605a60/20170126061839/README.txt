Tegra baseline test results for 20170126061839_f37208bc3c9c2f811460ef264909dfbc7f605a60


Here are some basic Tegra test results for Linux 20170126061839_f37208bc3c9c2f811460ef264909dfbc7f605a60.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20170126061839_f37208bc3c9c2f811460ef264909dfbc7f605a60/20170126061839/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    FAIL: ( 1/ 4): qemu-vexpress64
    Pass: ( 3/ 4): tegra132-norrin, tegra210-p2371-0000, tegra210-smaug

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
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_20170126061839_f37208bc3c9c2f811460ef264909dfbc7f605a60
Test-Serial: 20170126061839
Commit-ID: f37208bc3c9c2f811460ef264909dfbc7f605a60
Test-Target-Board-Count: 9
Test-Boot-Count: 14

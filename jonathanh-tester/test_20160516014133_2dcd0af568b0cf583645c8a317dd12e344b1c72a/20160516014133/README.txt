Tegra baseline test results for 20160516014133_2dcd0af568b0cf583645c8a317dd12e344b1c72a


Here are some basic Tegra test results for Linux 20160516014133_2dcd0af568b0cf583645c8a317dd12e344b1c72a.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20160516014133_2dcd0af568b0cf583645c8a317dd12e344b1c72a/20160516014133/


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
    FAIL: ( 1/ 4): tegra30-beaver
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice

PM: System suspend: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_20160516014133_2dcd0af568b0cf583645c8a317dd12e344b1c72a
Test-Serial: 20160516014133
Commit-ID: 2dcd0af568b0cf583645c8a317dd12e344b1c72a
Test-Target-Board-Count: 5
Test-Boot-Count: 9

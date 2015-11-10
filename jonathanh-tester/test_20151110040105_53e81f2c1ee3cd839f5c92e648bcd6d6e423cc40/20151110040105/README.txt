Tegra baseline test results for 20151110040105_53e81f2c1ee3cd839f5c92e648bcd6d6e423cc40


Here are some basic Tegra test results for Linux 20151110040105_53e81f2c1ee3cd839f5c92e648bcd6d6e423cc40.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20151110040105_53e81f2c1ee3cd839f5c92e648bcd6d6e423cc40/20151110040105/


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
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_20151110040105_53e81f2c1ee3cd839f5c92e648bcd6d6e423cc40
Test-Serial: 20151110040105
Commit-ID: 53e81f2c1ee3cd839f5c92e648bcd6d6e423cc40
Test-Target-Board-Count: 5
Test-Boot-Count: 9

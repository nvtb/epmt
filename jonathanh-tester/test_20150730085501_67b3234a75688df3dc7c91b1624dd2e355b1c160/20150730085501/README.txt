Tegra baseline test results for 20150730085501_67b3234a75688df3dc7c91b1624dd2e355b1c160


Here are some basic Tegra test results for Linux 20150730085501_67b3234a75688df3dc7c91b1624dd2e355b1c160.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20150730085501_67b3234a75688df3dc7c91b1624dd2e355b1c160/20150730085501/


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
Branch: test_20150730085501_67b3234a75688df3dc7c91b1624dd2e355b1c160
Test-Serial: 20150730085501
Commit-ID: 67b3234a75688df3dc7c91b1624dd2e355b1c160
Test-Target-Board-Count: 5
Test-Boot-Count: 9

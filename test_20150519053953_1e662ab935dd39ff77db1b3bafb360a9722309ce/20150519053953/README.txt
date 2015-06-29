Tegra baseline test results for 20150519053953_1e662ab935dd39ff77db1b3bafb360a9722309ce


Here are some basic Tegra test results for Linux 20150519053953_1e662ab935dd39ff77db1b3bafb360a9722309ce.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150519053953_1e662ab935dd39ff77db1b3bafb360a9722309ce/20150519053953/


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
    FAIL: ( 1/ 4): tegra20-trimslice
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_20150519053953_1e662ab935dd39ff77db1b3bafb360a9722309ce
Test-Serial: 20150519053953
Commit-ID: 1e662ab935dd39ff77db1b3bafb360a9722309ce
Test-Target-Board-Count: 5
Test-Boot-Count: 9

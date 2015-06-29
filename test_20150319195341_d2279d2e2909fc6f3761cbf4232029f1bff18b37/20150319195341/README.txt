Tegra baseline test results for 20150319195341_d2279d2e2909fc6f3761cbf4232029f1bff18b37


Here are some basic Tegra test results for Linux 20150319195341_d2279d2e2909fc6f3761cbf4232029f1bff18b37.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150319195341_d2279d2e2909fc6f3761cbf4232029f1bff18b37/20150319195341/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): multi_v7_defconfig
    Pass: ( 1/ 2): tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_20150319195341_d2279d2e2909fc6f3761cbf4232029f1bff18b37
Test-Serial: 20150319195341
Commit-ID: d2279d2e2909fc6f3761cbf4232029f1bff18b37
Test-Target-Board-Count: 5
Test-Boot-Count: 8

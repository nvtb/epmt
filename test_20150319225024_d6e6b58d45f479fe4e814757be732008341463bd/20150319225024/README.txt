Tegra baseline test results for 20150319225024_d6e6b58d45f479fe4e814757be732008341463bd


Here are some basic Tegra test results for Linux 20150319225024_d6e6b58d45f479fe4e814757be732008341463bd.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150319225024_d6e6b58d45f479fe4e814757be732008341463bd/20150319225024/


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
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150319225024_d6e6b58d45f479fe4e814757be732008341463bd
Test-Serial: 20150319225024
Commit-ID: d6e6b58d45f479fe4e814757be732008341463bd
Test-Target-Board-Count: 5
Test-Boot-Count: 8

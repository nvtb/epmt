Tegra baseline test results for 20150501025100_ba5ed02bec86490224b8d162ef1911869516d51e


Here are some basic Tegra test results for Linux 20150501025100_ba5ed02bec86490224b8d162ef1911869516d51e.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150501025100_ba5ed02bec86490224b8d162ef1911869516d51e/20150501025100/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver
    Pass: ( 1/ 4): tegra20-trimslice

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150501025100_ba5ed02bec86490224b8d162ef1911869516d51e
Test-Serial: 20150501025100
Commit-ID: ba5ed02bec86490224b8d162ef1911869516d51e
Test-Target-Board-Count: 5
Test-Boot-Count: 9

Tegra baseline test results for 20150325144058_6af714b069dc278d5d8e1b7afc13568f71d9aba8


Here are some basic Tegra test results for Linux 20150325144058_6af714b069dc278d5d8e1b7afc13568f71d9aba8.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150325144058_6af714b069dc278d5d8e1b7afc13568f71d9aba8/20150325144058/


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
Branch: test_20150325144058_6af714b069dc278d5d8e1b7afc13568f71d9aba8
Test-Serial: 20150325144058
Commit-ID: 6af714b069dc278d5d8e1b7afc13568f71d9aba8
Test-Target-Board-Count: 5
Test-Boot-Count: 9

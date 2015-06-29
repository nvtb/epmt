Tegra baseline test results for 20150519061107_8d5ae2aeafa78eca9fd0d92d4069960782deb761


Here are some basic Tegra test results for Linux 20150519061107_8d5ae2aeafa78eca9fd0d92d4069960782deb761.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150519061107_8d5ae2aeafa78eca9fd0d92d4069960782deb761/20150519061107/


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
Branch: test_20150519061107_8d5ae2aeafa78eca9fd0d92d4069960782deb761
Test-Serial: 20150519061107
Commit-ID: 8d5ae2aeafa78eca9fd0d92d4069960782deb761
Test-Target-Board-Count: 5
Test-Boot-Count: 9

Tegra baseline test results for 20150511203324_f17107cb8886e291269242246bda0a3ddfadaab0


Here are some basic Tegra test results for Linux 20150511203324_f17107cb8886e291269242246bda0a3ddfadaab0.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150511203324_f17107cb8886e291269242246bda0a3ddfadaab0/20150511203324/


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
Branch: test_20150511203324_f17107cb8886e291269242246bda0a3ddfadaab0
Test-Serial: 20150511203324
Commit-ID: f17107cb8886e291269242246bda0a3ddfadaab0
Test-Target-Board-Count: 5
Test-Boot-Count: 9

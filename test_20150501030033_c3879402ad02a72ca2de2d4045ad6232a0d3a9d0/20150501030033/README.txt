Tegra baseline test results for 20150501030033_c3879402ad02a72ca2de2d4045ad6232a0d3a9d0


Here are some basic Tegra test results for Linux 20150501030033_c3879402ad02a72ca2de2d4045ad6232a0d3a9d0.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150501030033_c3879402ad02a72ca2de2d4045ad6232a0d3a9d0/20150501030033/


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
Branch: test_20150501030033_c3879402ad02a72ca2de2d4045ad6232a0d3a9d0
Test-Serial: 20150501030033
Commit-ID: c3879402ad02a72ca2de2d4045ad6232a0d3a9d0
Test-Target-Board-Count: 5
Test-Boot-Count: 9

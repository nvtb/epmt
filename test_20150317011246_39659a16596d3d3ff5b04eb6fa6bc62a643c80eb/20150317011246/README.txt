Tegra baseline test results for 20150317011246_39659a16596d3d3ff5b04eb6fa6bc62a643c80eb


Here are some basic Tegra test results for Linux 20150317011246_39659a16596d3d3ff5b04eb6fa6bc62a643c80eb.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150317011246_39659a16596d3d3ff5b04eb6fa6bc62a643c80eb/20150317011246/


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
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_20150317011246_39659a16596d3d3ff5b04eb6fa6bc62a643c80eb
Test-Serial: 20150317011246
Commit-ID: 39659a16596d3d3ff5b04eb6fa6bc62a643c80eb
Test-Target-Board-Count: 4
Test-Boot-Count: 7

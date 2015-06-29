Tegra baseline test results for 20150319083701_e020abef280a4955a1a49e2a1fcdc059855fd046


Here are some basic Tegra test results for Linux 20150319083701_e020abef280a4955a1a49e2a1fcdc059855fd046.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150319083701_e020abef280a4955a1a49e2a1fcdc059855fd046/20150319083701/


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
Branch: test_20150319083701_e020abef280a4955a1a49e2a1fcdc059855fd046
Test-Serial: 20150319083701
Commit-ID: e020abef280a4955a1a49e2a1fcdc059855fd046
Test-Target-Board-Count: 5
Test-Boot-Count: 8

Tegra baseline test results for 20150511204703_3838232431c2636ff539f2354c630c0ca3d4b7ad


Here are some basic Tegra test results for Linux 20150511204703_3838232431c2636ff539f2354c630c0ca3d4b7ad.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150511204703_3838232431c2636ff539f2354c630c0ca3d4b7ad/20150511204703/


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
Branch: test_20150511204703_3838232431c2636ff539f2354c630c0ca3d4b7ad
Test-Serial: 20150511204703
Commit-ID: 3838232431c2636ff539f2354c630c0ca3d4b7ad
Test-Target-Board-Count: 5
Test-Boot-Count: 9

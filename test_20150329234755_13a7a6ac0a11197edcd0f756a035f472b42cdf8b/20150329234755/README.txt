Tegra baseline test results for 20150329234755_13a7a6ac0a11197edcd0f756a035f472b42cdf8b


Here are some basic Tegra test results for Linux 20150329234755_13a7a6ac0a11197edcd0f756a035f472b42cdf8b.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150329234755_13a7a6ac0a11197edcd0f756a035f472b42cdf8b/20150329234755/


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
Branch: test_20150329234755_13a7a6ac0a11197edcd0f756a035f472b42cdf8b
Test-Serial: 20150329234755
Commit-ID: 13a7a6ac0a11197edcd0f756a035f472b42cdf8b
Test-Target-Board-Count: 5
Test-Boot-Count: 9

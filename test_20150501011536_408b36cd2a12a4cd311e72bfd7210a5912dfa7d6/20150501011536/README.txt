Tegra baseline test results for 20150501011536_408b36cd2a12a4cd311e72bfd7210a5912dfa7d6


Here are some basic Tegra test results for Linux 20150501011536_408b36cd2a12a4cd311e72bfd7210a5912dfa7d6.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150501011536_408b36cd2a12a4cd311e72bfd7210a5912dfa7d6/20150501011536/


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
Branch: test_20150501011536_408b36cd2a12a4cd311e72bfd7210a5912dfa7d6
Test-Serial: 20150501011536
Commit-ID: 408b36cd2a12a4cd311e72bfd7210a5912dfa7d6
Test-Target-Board-Count: 5
Test-Boot-Count: 9

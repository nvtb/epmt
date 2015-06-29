Tegra baseline test results for 20150501031229_f4f4e07b467f9021434482ee2a7ffc7b30279f7f


Here are some basic Tegra test results for Linux 20150501031229_f4f4e07b467f9021434482ee2a7ffc7b30279f7f.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150501031229_f4f4e07b467f9021434482ee2a7ffc7b30279f7f/20150501031229/


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
Branch: test_20150501031229_f4f4e07b467f9021434482ee2a7ffc7b30279f7f
Test-Serial: 20150501031229
Commit-ID: f4f4e07b467f9021434482ee2a7ffc7b30279f7f
Test-Target-Board-Count: 5
Test-Boot-Count: 9

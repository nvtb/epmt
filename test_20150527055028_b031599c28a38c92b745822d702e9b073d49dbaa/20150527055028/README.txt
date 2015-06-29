Tegra baseline test results for 20150527055028_b031599c28a38c92b745822d702e9b073d49dbaa


Here are some basic Tegra test results for Linux 20150527055028_b031599c28a38c92b745822d702e9b073d49dbaa.
Logs and other details at:

    http://nvt.pwsan.com/pub/jonathanh-tester/testlogs/test_20150527055028_b031599c28a38c92b745822d702e9b073d49dbaa/20150527055028/


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
Branch: test_20150527055028_b031599c28a38c92b745822d702e9b073d49dbaa
Test-Serial: 20150527055028
Commit-ID: b031599c28a38c92b745822d702e9b073d49dbaa
Test-Target-Board-Count: 5
Test-Boot-Count: 9

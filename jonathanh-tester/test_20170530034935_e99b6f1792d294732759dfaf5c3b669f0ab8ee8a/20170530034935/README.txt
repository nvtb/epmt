Tegra baseline test results for 20170530034935_e99b6f1792d294732759dfaf5c3b669f0ab8ee8a


Here are some basic Tegra test results for Linux 20170530034935_e99b6f1792d294732759dfaf5c3b669f0ab8ee8a.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20170530034935_e99b6f1792d294732759dfaf5c3b669f0ab8ee8a/20170530034935/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_20170530034935_e99b6f1792d294732759dfaf5c3b669f0ab8ee8a
Test-Serial: 20170530034935
Commit-ID: e99b6f1792d294732759dfaf5c3b669f0ab8ee8a
Test-Target-Board-Count: 9
Test-Boot-Count: 14

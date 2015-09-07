Tegra baseline test results for 20150907122634_80b0ee7ba807fdd44d575ae4dd069229abc381a4


Here are some basic Tegra test results for Linux 20150907122634_80b0ee7ba807fdd44d575ae4dd069229abc381a4.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20150907122634_80b0ee7ba807fdd44d575ae4dd069229abc381a4/20150907122634/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150907122634_80b0ee7ba807fdd44d575ae4dd069229abc381a4
Test-Serial: 20150907122634
Commit-ID: 80b0ee7ba807fdd44d575ae4dd069229abc381a4
Test-Target-Board-Count: 5
Test-Boot-Count: 9

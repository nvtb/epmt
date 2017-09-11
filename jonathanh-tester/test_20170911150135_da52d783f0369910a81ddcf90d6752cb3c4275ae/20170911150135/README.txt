Tegra baseline test results for 20170911150135_da52d783f0369910a81ddcf90d6752cb3c4275ae


Here are some basic Tegra test results for Linux 20170911150135_da52d783f0369910a81ddcf90d6752cb3c4275ae.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20170911150135_da52d783f0369910a81ddcf90d6752cb3c4275ae/20170911150135/


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
    FAIL: ( 2/ 5): tegra124-nyan-big, tegra30-beaver
    Pass: ( 3/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 5): tegra20-trimslice
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver


-------------------------------------------------------------
Branch: test_20170911150135_da52d783f0369910a81ddcf90d6752cb3c4275ae
Test-Serial: 20170911150135
Commit-ID: da52d783f0369910a81ddcf90d6752cb3c4275ae
Test-Target-Board-Count: 9
Test-Boot-Count: 14

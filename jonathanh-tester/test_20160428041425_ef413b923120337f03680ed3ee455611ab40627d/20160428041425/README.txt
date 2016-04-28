Tegra baseline test results for 20160428041425_ef413b923120337f03680ed3ee455611ab40627d


Here are some basic Tegra test results for Linux 20160428041425_ef413b923120337f03680ed3ee455611ab40627d.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20160428041425_ef413b923120337f03680ed3ee455611ab40627d/20160428041425/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 3/ 3): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_20160428041425_ef413b923120337f03680ed3ee455611ab40627d
Test-Serial: 20160428041425
Commit-ID: ef413b923120337f03680ed3ee455611ab40627d
Test-Target-Board-Count: 5
Test-Boot-Count: 9

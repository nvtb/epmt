Tegra baseline test results for 20170703131819_2ee9835c64e42d13d329170deba7b2ebb46345e1


Here are some basic Tegra test results for Linux 20170703131819_2ee9835c64e42d13d329170deba7b2ebb46345e1.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20170703131819_2ee9835c64e42d13d329170deba7b2ebb46345e1/20170703131819/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    WARN: ( 1/ 4): qemu-vexpress64
    Pass: ( 3/ 4): tegra132-norrin, tegra210-p2371-0000, tegra210-smaug

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
Branch: test_20170703131819_2ee9835c64e42d13d329170deba7b2ebb46345e1
Test-Serial: 20170703131819
Commit-ID: 2ee9835c64e42d13d329170deba7b2ebb46345e1
Test-Target-Board-Count: 9
Test-Boot-Count: 14

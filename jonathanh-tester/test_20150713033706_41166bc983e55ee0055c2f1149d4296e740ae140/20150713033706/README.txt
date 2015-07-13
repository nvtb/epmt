Tegra baseline test results for 20150713033706_41166bc983e55ee0055c2f1149d4296e740ae140


Here are some basic Tegra test results for Linux 20150713033706_41166bc983e55ee0055c2f1149d4296e740ae140.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20150713033706_41166bc983e55ee0055c2f1149d4296e740ae140/20150713033706/


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
Branch: test_20150713033706_41166bc983e55ee0055c2f1149d4296e740ae140
Test-Serial: 20150713033706
Commit-ID: 41166bc983e55ee0055c2f1149d4296e740ae140
Test-Target-Board-Count: 5
Test-Boot-Count: 9

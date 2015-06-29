Tegra baseline test results for 20150325105350_4a3a6f86693922b29cf829c63f652b057f14619e


Here are some basic Tegra test results for Linux 20150325105350_4a3a6f86693922b29cf829c63f652b057f14619e.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150325105350_4a3a6f86693922b29cf829c63f652b057f14619e/20150325105350/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra20-trimslice
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150325105350_4a3a6f86693922b29cf829c63f652b057f14619e
Test-Serial: 20150325105350
Commit-ID: 4a3a6f86693922b29cf829c63f652b057f14619e
Test-Target-Board-Count: 5
Test-Boot-Count: 9

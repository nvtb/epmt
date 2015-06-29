Tegra baseline test results for 20150604122454_0ba689090bdac347f87b8f5892552d4f8b1b6a78


Here are some basic Tegra test results for Linux 20150604122454_0ba689090bdac347f87b8f5892552d4f8b1b6a78.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150604122454_0ba689090bdac347f87b8f5892552d4f8b1b6a78/20150604122454/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): multi_v7_defconfig
    Pass: ( 1/ 2): tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_20150604122454_0ba689090bdac347f87b8f5892552d4f8b1b6a78
Test-Serial: 20150604122454
Commit-ID: 0ba689090bdac347f87b8f5892552d4f8b1b6a78
Test-Target-Board-Count: 5
Test-Boot-Count: 9

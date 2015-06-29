Tegra baseline test results for 20150319184814_173bfba8016d45725e996c8f7239817b779afa0a


Here are some basic Tegra test results for Linux 20150319184814_173bfba8016d45725e996c8f7239817b779afa0a.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150319184814_173bfba8016d45725e996c8f7239817b779afa0a/20150319184814/


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
Branch: test_20150319184814_173bfba8016d45725e996c8f7239817b779afa0a
Test-Serial: 20150319184814
Commit-ID: 173bfba8016d45725e996c8f7239817b779afa0a
Test-Target-Board-Count: 5
Test-Boot-Count: 8

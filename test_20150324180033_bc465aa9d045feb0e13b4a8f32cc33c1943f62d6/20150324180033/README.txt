Tegra baseline test results for 20150324180033_bc465aa9d045feb0e13b4a8f32cc33c1943f62d6


Here are some basic Tegra test results for Linux 20150324180033_bc465aa9d045feb0e13b4a8f32cc33c1943f62d6.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150324180033_bc465aa9d045feb0e13b4a8f32cc33c1943f62d6/20150324180033/


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
Branch: test_20150324180033_bc465aa9d045feb0e13b4a8f32cc33c1943f62d6
Test-Serial: 20150324180033
Commit-ID: bc465aa9d045feb0e13b4a8f32cc33c1943f62d6
Test-Target-Board-Count: 5
Test-Boot-Count: 9

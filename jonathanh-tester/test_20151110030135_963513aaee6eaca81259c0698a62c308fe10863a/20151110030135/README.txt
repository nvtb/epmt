Tegra baseline test results for 20151110030135_963513aaee6eaca81259c0698a62c308fe10863a


Here are some basic Tegra test results for Linux 20151110030135_963513aaee6eaca81259c0698a62c308fe10863a.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20151110030135_963513aaee6eaca81259c0698a62c308fe10863a/20151110030135/


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
Branch: test_20151110030135_963513aaee6eaca81259c0698a62c308fe10863a
Test-Serial: 20151110030135
Commit-ID: 963513aaee6eaca81259c0698a62c308fe10863a
Test-Target-Board-Count: 5
Test-Boot-Count: 9

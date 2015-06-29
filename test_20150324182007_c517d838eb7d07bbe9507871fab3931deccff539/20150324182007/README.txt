Tegra baseline test results for 20150324182007_c517d838eb7d07bbe9507871fab3931deccff539


Here are some basic Tegra test results for Linux 20150324182007_c517d838eb7d07bbe9507871fab3931deccff539.
Logs and other details at:

    http://nvt.pwsan.com/pub/pwalmsley-tester/testlogs/test_20150324182007_c517d838eb7d07bbe9507871fab3931deccff539/20150324182007/


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
Branch: test_20150324182007_c517d838eb7d07bbe9507871fab3931deccff539
Test-Serial: 20150324182007
Commit-ID: c517d838eb7d07bbe9507871fab3931deccff539
Test-Target-Board-Count: 5
Test-Boot-Count: 9

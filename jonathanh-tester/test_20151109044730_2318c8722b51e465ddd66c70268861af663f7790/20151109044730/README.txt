Tegra baseline test results for 20151109044730_2318c8722b51e465ddd66c70268861af663f7790


Here are some basic Tegra test results for Linux 20151109044730_2318c8722b51e465ddd66c70268861af663f7790.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20151109044730_2318c8722b51e465ddd66c70268861af663f7790/20151109044730/


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
Branch: test_20151109044730_2318c8722b51e465ddd66c70268861af663f7790
Test-Serial: 20151109044730
Commit-ID: 2318c8722b51e465ddd66c70268861af663f7790
Test-Target-Board-Count: 5
Test-Boot-Count: 9

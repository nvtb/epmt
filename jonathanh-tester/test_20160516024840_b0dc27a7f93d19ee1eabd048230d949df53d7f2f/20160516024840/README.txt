Tegra baseline test results for 20160516024840_b0dc27a7f93d19ee1eabd048230d949df53d7f2f


Here are some basic Tegra test results for Linux 20160516024840_b0dc27a7f93d19ee1eabd048230d949df53d7f2f.
Logs and other details at:

    https://nvtb.github.io//epmt/jonathanh-tester/test_20160516024840_b0dc27a7f93d19ee1eabd048230d949df53d7f2f/20160516024840/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 2/ 4): tegra114-dalmore-a04, tegra30-beaver
    Pass: ( 2/ 4): tegra124-jetson-tk1, tegra20-trimslice

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_20160516024840_b0dc27a7f93d19ee1eabd048230d949df53d7f2f
Test-Serial: 20160516024840
Commit-ID: b0dc27a7f93d19ee1eabd048230d949df53d7f2f
Test-Target-Board-Count: 5
Test-Boot-Count: 9

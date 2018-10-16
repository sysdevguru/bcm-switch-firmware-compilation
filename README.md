# bcm-switch-firmware-compilation

- bcm53346.sh
Setting environment variables for the compilation.

- sdk-xgs-robo-6.5.7.tar.gz
This is the SDK of Broadcom Robo Chip.

## bin.user.proxy and u-boot.bin compilation
```
$./bcm53346.sh
$tar -xvzf sdk-xgs-robo-6.5.7.tar.gz
$cd sdk-xgs-robo-6.5.7/systems/linux/kernel
$mkdir iproc
$cd common
$make
```
The bcm.user.proxy will be compiled into the directory sdk-xgs-robo-6.5.7/build/linux/kernel/common
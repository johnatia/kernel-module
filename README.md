# kernel-module
let's build our first kernel module on raspberrypi


to configure RaspberryPi for kernel development
install kernel headers
```
sudo apt update & sudo apt upgrade
```
```
sudo apt install raspberrypi-kernel-headers
```

to know the kernel version just type
```
uname -r
```

check the build options
```
ls /lib/modules/$(uname -r)/build
```
now we can start building kernel module

then try hello world example

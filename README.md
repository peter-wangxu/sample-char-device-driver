# sample-char-device-driver
A sample character device driver from scratch

This is a sample character device driver for Linux:
a full guide locates here: https://sysplay.github.io/books/LinuxDrivers/book/Content/Part05.html


## Build

```bash
git clone https://github.com/peter-wangxu/sample-char-device-driver
cd sample-char-device-driver
make

```

## Test and Verify

- Build the driver (.ko file) by running make.
- Load the driver using insmod.
- List the loaded modules using lsmod.
- List the major number allocated using cat /proc/devices.
- "null driver" specific experiments (Refer to Figure below for details).
- Unload the driver using rmmod.

![verify](https://sysplay.github.io/books/LinuxDrivers/book/Images/Part5/figure_10_null_driver_experiments.png)

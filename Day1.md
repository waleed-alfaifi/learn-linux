Background and Introduction

- Linux can refer to the operating system
- Can refer to Linux Kernel

A distribution is the Linux Kernel plus additional software.

**Linux Kernel** is the heart of the Linux OS.

## Directory Structure

### Common Directories

- `/` Root, the top of the file system hierarchy
- `/bin` Binaries and other executable programs
- `/etc` System configuration file, e.g. there is a config file in /etc that tells the OS whether to boot in text mode or graphical mode
- `/home` Home directory, is where users data is stored. Users have different home directories, for example home directory for a user named john is /home/john. There is an exception for the root user where its home directory is /root.
- `/opt` Optional or third party software, for example google chrome, or avg anti-virus will become /opt/google/chrome and /opt/avg respectively.
- `/temp` Temporary space, typically cleared on reboot
- `/usr` User related programs, just like home directory, e.g. you can have /usr/john directory that can have bin files for example like /usr/john/bin
- `/var` Variable data, things that change often, like log files

![](./cd1.png)

![](./cd2.png)

### Comprehensive Listing

> You can find a comprehensive listing of directories in this file: [](./Linux-Directory-Structure.pdf)

- `/boot` Files needed to boot the system

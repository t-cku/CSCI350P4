# CS350P4

### USC emails:
tcku@usc.edu

### How to compile:
cd xv6-public-master
make TOOLPREFIX=i686-elf- qemu-nox
With the standard xv6 toolchain, plain "make qemu-nox" will work. 


### How to run:
make qemu-nox starts xv6 iin QEMU.
At the 4 prompt, run:
testcow (copy-on-write test which calls procdump before/after the child writes)
Press CTRL-P to print the process list with the page mappings.
To quit QEMU, press CTRL-A and then X.


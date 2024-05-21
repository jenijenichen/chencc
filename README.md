编译.s汇编文件
riscv64-unknown-linux-gnu-gcc -static tmp.s -o tmp

运行tmp可执行文件
qemu-riscv64 -L $RISCV/sysroot tmp

编译main.c文件
clang main.c -o rvcc

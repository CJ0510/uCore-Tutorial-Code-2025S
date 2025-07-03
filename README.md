# P1

- bootloader：固件
- os：内核
    - console：控制台
    - defs.h：头文件包含
    - entry.S：内核入口程序
    - kernel.ld：链接文件
    - main.c：入口程序
    - printf：printf
    - riscv.h：定义
    - sbi：系统调用
移植rustsbi，链接https://github.com/rustsbi/rustsbi-k210/releases

完成ch-k210
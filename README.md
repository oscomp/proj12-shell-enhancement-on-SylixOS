# proj2x-SylixOS-porting-to-Raspberry-Pi
### 项目描述

SylixOS 全面支持 ARM / PowerPC / MIPS / x86 / SPARC / DSP / RISC-V / C-SKY， 同时支持主流半导体厂商的大量板卡和设备，部分支持列表可参考[翼辉官网](https://www.acoinfo.com/html/edu_con/cpu.html)。

低成本，高性能的Raspberry Pi（树莓派）计算机和配件，是为学习计算机编程教育而设计，在教育和创客领域非常流行。树莓派OS是基于Linux 发行版 Debian设计改造的。

目前主流的树莓派是Raspberry Pi 4，其芯片是BCM2711，处理器是4核的Cortex-A72 (ARM v8)   64-bit，SylixOS 内核已支持ARM 32-bit 和  ARM  64-bit (ARM v8)架构，并且SylixOS支持多核处理器 SMP运行。

我们的目标是在Raspberry Pi 4 上完成 SylixOS 最小系统开发适配和基础功能开发，SylixOS最小系统包括系统时钟、系统中断和串口通信功能，基础功能包括网络通信与存储等功能。

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

葛文斌

* github [databuser](https://github.com/databuser)
* email  gewenbin@acoinfo.com


### 难度

第一题 、第二题：中等 ， 第三题：困难


### 特征

- 参考am335的BSP实现，了解SylixOS系统引导启动流程
- 在树莓派上完成SylixOS最小系统运行，并实现通过串口进行shell交互
- 需要熟练掌握C语言，了解ARM汇编指令

### 文档

[SylixOS 最小系统开发适配指导文档](https://github.com/acoinfo/sylixos_oscomp_2021/tree/master/SylixOS-porting-to-Raspberry-Pi)

### 参考代码
* [bspam335x](http://git.sylixos.com/cgit/cgit.cgi/bspam335x.git/)

### License

*  [The MIT License](https://opensource.org/licenses/MIT)

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：完成SylixOS CPU单核启动最小系统开发

*  完成SylixOS 在Raspberry Pi 4上引导启动和初始化，完成ARM 32-bit或ARM 64-bit和CPU单核启动
* 完成系统时钟和系统中断功能
* 可以进行串口通信

### 第二题：完成SylixOS CPU多核启动最小系统开发

* 完成SylixOS 在Raspberry Pi 4上引导启动和初始化，完成ARM 32-bit或ARM 64-bit和CPU多核启动
* 完成系统时钟和系统中断功能
* 能进行串口通信

### 第三题： 完成SylixOS 的网络通信和存储功能

* 完成第二题中多核启动最小系统

* 完成以太网网卡的网络通信功能

* 完成SD卡的存储功能

  
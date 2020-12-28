# proj12-shell-enhancement-on-SylixOS
### 项目描述

SylixOS 是中国自主可控的大型实时操作系统，于二零零六年开始研发，经过多年的持续开发与改进，SylixOS 已经成为一个功能全面，稳定可靠，易于开发的实时系统平台。

SylixOS 是中国人完全自主设计开发，内核开源的操作系统。目前功能已非常完备，在国防、航空航天、电力、轨道交通、 工业自动化 等领域有着广泛的应用。

SylixOS 已拥有一套命令行的实现机制，拥有丰富且实用的shell 命令行，并具备简单的shell脚本能力。

我们的目标是设计并完善命令行机制，增强shell命令行编程能力，目的是帮助学生深入理解操作系统的人机交互，掌握操作系统交互和编程语言的设计和实现。

- 实现命令行自动补全、联想帮助、管道、过滤和分屏显示机制

- 增强 Shell 命令行编程能力

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

**陈洪邦**

* github

* email chenhongbang@acoinfo.com


### 难度

中等


### 特征

- 兼容 SylixOS 命令行实现，可在此基础上进行功能扩增；
- 实现命令行关键字的自动补全，例如 if?  回车后，打印if开头的命令行关键字，按Tab键可以直接补全或切换（多个选项时），if?  ifconfig；

- 实现命令行关键字和参数的联想帮助，例如：ifconfig  ?  回车后，打印此命令后面可以输入的关键字或参数。

### 文档

[SylixOS shell增强开发指导文档](https://github.com/acoinfo/sylixos_oscomp_2021/tree/master/shell_enhancement)

[SylixOS shell用户手册](https://github.com/acoinfo/sylixos_oscomp_2021/tree/master/shell_enhancement)

### 源代码
* [libcextern.git](http://git.sylixos.com/cgit/cgit.cgi/libcextern.git/) 

* [libsylixos.git](http://git.sylixos.com/cgit/cgit.cgi/libsylixos.git/) 

### License

* [The MIT License](https://opensource.org/licenses/MIT)

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：实现命令行自动补全、联想帮助、管道、过滤和分屏显示机制

* 实现命令行关键字的自动补全功能
* 实现命令行关键字和参数的联想帮助
* 实现命令之间的管道操作 |，支持输出过滤和分屏显示

### 第二题：增强 Shell 命令行编程能力

* 支持分支语句，if/elif/else
* 支持循环语句，while/for，支持 break/continue
* 支持 find、grep、awk、sed 实用命令

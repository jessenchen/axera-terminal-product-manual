# 性能介绍

本章整理 AXERA 终端计算芯片在运行传统的IPC样例程序上的实测性能，并记录 OS:CMM、卡端 DDR、固件/驱动等复现所需的环境信息。
目前已收录的数据主要来自内部测试以及已量产项目，后续会随测试的进一步完善继续补充。

```{toctree}
:maxdepth: 1

ax620_module_perfermance_introduction
ax630_module_perfermance_introduction
ax615_module_perfermance_introduction
ax637_module_perfermance_introduction
```

**章节目录**
- **[2.1.1 AX620模块性能介绍](./ax620_module_perfermance_introduction.md)**
- **[2.1.2 AX630模块性能介绍](./ax630_module_perfermance_introduction.md)**
- **[2.1.3 AX615模块性能介绍](./ax615_module_perfermance_introduction.md)**
- **[2.1.4 AX637模块性能介绍](./ax637_module_perfermance_introduction.md)**

**内容介绍**
- **perfermance_overview 综述**：测试条件、环境信息与数据记录规范，并说明查看各硬件模块的时钟、NPU DDR 带宽及带宽限制检查方法。
- **性能内容**：以芯片型号划分，记录：主频、DDR容量、算力、VIN并发能力、MM处理性能、视频编解码、图片编解码能力，
并记录具体型号芯片支持以几路MIPI、多大分辨率输入情况，以表格的样式呈现给读者。


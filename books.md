标签：os, kernel, ebpf, perf, tracing, networking, compiler, linker-loader, systems, arch, c-cpp, rust, security, database, distributed, embedded, driver, arm, risc-v, gpu, math, algo, tooling, career, en, toc, notoc, text, scan

- toc :有目录
- notoc: 无目录
- text: 文字版
- scan: 扫描版

| name                                           | tags               |  rate | comment      |
| ---------------------------------------------- | ------------------ | ----: | ------------ |
| **系统架构**                                       |                    |       |              |
| 计算机体系结构：量化研究方法（第五版）                            | arch,systems       |  ⭐⭐⭐⭐ | 建模权衡，架构经典    |
| 面向现代硬件的算法                                      | algo,arch          |   ⭐⭐⭐ | 硬件感知算法       |
| RISC-V-Reader-Chinese                          | arch,risc-v        |   ⭐⭐⭐ | RISC-V 入门    |
| 深入理解计算机系统                                      | systems,arch       | ⭐⭐⭐⭐⭐ | 体系化必读        |
| 深入理解并行编程                                       | systems            |   ⭐⭐⭐ | 观念好，偏旧       |
| What Every Programmer Should Know About Memory | arch,systems,en    |  ⭐⭐⭐⭐ | 内存/NUMA综述    |
| x86汇编语言：从实模式到保护模式                              | arch,systems       |   ⭐⭐⭐ | x86 汇编路径     |
| **操作系统**                                       |                    |       |              |
| 奔跑吧Linux内核（第2版）卷1：基础架构                         | kernel,os          |  ⭐⭐⭐⭐ | 实战友好         |
| 奔跑吧Linux内核（第2版）卷2：调试与案例分析                      | kernel,os          |  ⭐⭐⭐⭐ | 调试案例扎实       |
| 操作系统导论-OSTEP                                   | os                 | ⭐⭐⭐⭐⭐ | 清晰可实验        |
| 操作系统真象还原                                       | os                 |   ⭐⭐⭐ | 自制 OS 体验     |
| 深度探索Linux操作系统：系统构建和原理解析                        | os,kernel          |   ⭐⭐⭐ | 构建视角         |
| 深度探索Linux系统虚拟化                                 | os,kernel          |   ⭐⭐⭐ | 虚拟化综述        |
| 深入Linux内核架构                                    | kernel,os          |   ⭐⭐⭐ | 体系强/偏旧       |
| Linux操作系统原理与应用                                 | os,kernel          |   ⭐⭐⭐ | 教材取向         |
| Linux内核设计与实现                                   | kernel,os          |   ⭐⭐⭐ | 全景/版本旧       |
| Linux内核精髓                                      | kernel,os          |   ⭐⭐⭐ | 技巧杂锦         |
| Linux内核深度解析 基于ARM64架构                          | kernel,os,arm      |  ⭐⭐⭐⭐ | 贴 ARM64 实务   |
| Linux内核完全注释                                    | kernel,os          |     ⭐ | 过时慎读         |
| Linux内核源代码情景分析                                 | kernel,os          |    ⭐⭐ | 老版参考         |
| 现代操作系统：原理与实现                                   | os,kernel          |   ⭐⭐⭐ | 教材风          |
| 虚拟化技术：什么是虚拟机                                   | os                 |   ⭐⭐⭐ | 入门可          |
| 自研操作系统：DIM-SUM设计与实现                            | os                 |   ⭐⭐⭐ | 个案参考         |
| **网络编程**                                       |                    |       |              |
| 深入理解Linux网络                                    | networking,kernel  |  ⭐⭐⭐⭐ | 内核路径清晰       |
| UNIX网络编程 卷2 进程间通信                              | networking,systems |  ⭐⭐⭐⭐ | IPC 纵深       |
| UNIX环境高级编程                                     | systems            | ⭐⭐⭐⭐⭐ | UNIX 基石      |
| **驱动开发**                                       |                    |       |              |
| Linux块设备驱动开发入门                                 | driver,kernel      |   ⭐⭐⭐ | 入门向          |
| Linux驱动开发入门                                    | driver,kernel      |   ⭐⭐⭐ | 上手可          |
| Linux设备驱动开发详解                                  | driver,kernel      |   ⭐⭐⭐ | 覆盖广/偏旧       |
| **嵌入式**                                        |                    |       |              |
| 常见flash讲解——NAND、SPI、EMMC                       | embedded           |    ⭐⭐ | 参差，配手册读      |
| FreeRTOS入门手册                                   | embedded,os        |   ⭐⭐⭐ | RTOS 入门      |
| Uboot启动过程详解                                    | embedded           |   ⭐⭐⭐ | SPL→内核脉络     |
| 嵌入式C语言自我修养                                     | embedded,c-cpp     |  ⭐⭐⭐⭐ | 嵌入式进阶        |
| 嵌入式Linux开发教程                                   | embedded,linux     |   ⭐⭐⭐ | 工程入门         |
| **编程语言**                                       |                    |       |              |
| C专家编程                                          | c-cpp              |  ⭐⭐⭐⭐ | 语义与陷阱        |
| 程序员的自我修养                                       | linker-loader      | ⭐⭐⭐⭐⭐ | ELF/ld.so 神作 |
| **eBPF/性能**                                    |                    |       |              |
| 2024 eBPF技术白皮书（第二版）                            | ebpf,kernel        |   ⭐⭐⭐ | 生态综述         |
| BPF之巅 洞悉Linux系统和应用性能                           | ebpf,perf,kernel   |  ⭐⭐⭐⭐ | 方法论强         |
| eBPF学习指南                                       | ebpf,kernel        |   ⭐⭐⭐ | 入门综述         |
| EBPF学习手册                                       | ebpf,kernel        |   ⭐⭐⭐ | 进阶补充         |
| **开发工具**                                       |                    |       |              |
| CS-Notes\_正则表达式                                | tooling            |   ⭐⭐⭐ | 速查即可         |
| Git权威指南                                        | tooling            |  ⭐⭐⭐⭐ | 系统讲解         |
| GNU Make 项目管理                                  | tooling            |  ⭐⭐⭐⭐ | 项目视角         |
| GNU Make手册                                     | tooling            |  ⭐⭐⭐⭐ | 权威参考         |
| GNU make v3.80完整版中文指南                          | tooling            |   ⭐⭐⭐ | 版本旧          |
| 跟我一起写makefile                                  | tooling            |  ⭐⭐⭐⭐ | 实例丰富         |
| Managing Projects with GNU Make                | tooling            |  ⭐⭐⭐⭐ | 英文实践         |
| progit-zh                                      | tooling            |  ⭐⭐⭐⭐ | 入门到进阶        |
| shell编程从入门到精通                                  | tooling            |    ⭐⭐ | 质量不一         |
| 手把手教你如何写Makefile                               | tooling            |   ⭐⭐⭐ | 入门向          |
| 正则表达式必知必会                                      | tooling            |  ⭐⭐⭐⭐ | 入门佳作         |
| **职业发展**                                       |                    |       |              |
| 持续交付2.0：业务引领的DevOps精要                          | career             |  ⭐⭐⭐⭐ | 工程可落地        |
| 大问题 简明哲学导论（第十版）                                | career             |   ⭐⭐⭐ | 思辨入门         |
| 代码整洁之道                                         | career             |  ⭐⭐⭐⭐ | 风格与习惯        |
| 人月神话（二十周年纪念版）                                  | career             |   ⭐⭐⭐ | 历史观念         |
| 实用性阅读指南                                        | career             |   ⭐⭐⭐ | 方法论          |
| 重构：改善既有代码的设计（第2版）                              | career             |  ⭐⭐⭐⭐ | 现代重构范式       |

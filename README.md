## secret-algorithm-base-freertos-riscv
基于RISC-V的FreeRTOS国密算法功能实现


## 项目描述
RISC-V（发音为“risk-five”）是一个基于精简指令集（RISC）原则的开源指令集架构（ISA）。与大多数指令集相比，RISC-V指令集可以自由地用于任何目的，允许任何人设计、制造和销售RISC-V芯片和软件。虽然这不是第一个开源指令集，但它具有重要意义，因为其设计使其适用于现代计算设备（如仓库规模云计算机、高端移动电话和微小嵌入式系统）。设计者考虑到了这些用途中的性能与功率效率。该指令集还具有众多支持的软件，这解决了新指令集通常的弱点。
Free 即免费的，RTOS 全称是 Real Time Operating System，中文就是实时操作系统。
FreeRTOS 是 RTOS 系统的一种，FreeRTOS 十分的小巧，可以在资源有限的微控制器中运行， FreeRTOS 也不仅仅局限于在微控制器中使用。
该项目基于RISC-V和FreeRTOS实现国密算法，以增强对数据的安全保护。

## 所属赛道

2022全国大学生操作系统比赛的“OS功能挑战”赛道



## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生（2022年春季学期或之后毕业的本科生及研究生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求



## 项目导师

* 武耀威: wuyaowei@kylinos.cn
* 张志成: zhangzhicheng@kylinos.cn



## 难度

中等


## 特征

* 使用 RISC-V架构
* 满足国密算法要求
* 满足性能要求
* 编写测试用例，满足测试要求、所有接口覆盖测试。


## License
任意开源license都可


## 预期目标
* 基于RISC-V架构在freertos实现国密算法，实现对数据的加密解密，同时要满足性能的要求。
* 实现基于freertos的SM3、SM4软算法。
* 选择本项目的同学也可提出自己的新想法，得到导师认可支持后亦可加入预期目标或进阶特性

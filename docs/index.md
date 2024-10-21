---
layout: post
title: HDLbits Verilog Notebook
nav_order: 0
description: "HDLbits Verilog Notebook"
permalink: /
---


# 开始

## Problem Sets 问题集

### Contents 目录
1. **Getting Started 入门**
2. **Verilog Language Verilog语言**
   1. **Basics 基础**
   2. **Vectors 向量**
   3. **Modules: Hierarchy 模块：层次结构**
   4. **Procedures 程序**
   5. **More Verilog Features 更多Verilog特性**
3. **Circuits 电路**
   1. **Combinational Logic 组合逻辑**
      1. **Basic Gates 基本门电路**
      2. **Multiplexers 多路复用器**
      3. **Arithmetic Circuits 算术电路**
      4. **Karnaugh Map to Circuit 卡诺图到电路**
   2. **Sequential Logic 时序逻辑**
      1. **Latches and Flip-Flops 锁存器和触发器**
      2. **Counters 计数器**
      3. **Shift Registers 移位寄存器**
      4. **More Circuits 更多电路**
      5. **Finite State Machines 有限状态机**
   3. **Building Larger Circuits 构建更大电路**
4. **Verification: Reading Simulations 验证：读取仿真**
   1. **Finding Bugs in Code 查找代码中的错误**
   2. **Build a Circuit from a Simulation Waveform 从仿真波形构建电路**
5. **Verification: Writing Testbenches 验证：编写测试平台**
6. **CS450**

---

### Getting Started 入门
**Getting Started 入门**

- **Output Zero 输出为零**

---

### Verilog Language Verilog语言
#### Basics 基础
- **Simple Wire 简单导线**
- **Four Wires 四根导线**
- **Inverter 反相器**
- **AND Gate 与门**
- **NOR Gate 或非门**
- **XNOR Gate 同或门**
- **Declaring Wires 声明导线**
- **7458 Chip 7458芯片**

---

#### Vectors 向量
- **Vectors 向量**
- **Vectors in More Detail 详细解释向量**
- **Vector Part Select 向量部分选择**
- **Bitwise Operators 按位操作符**
- **Four-Input Gates 四输入门电路**
- **Vector Concatenation Operator 向量连接操作符**
- **Vector Reversal 1 向量翻转 1**
- **Replication Operator 复制操作符**
- **More Replication 更多复制**

---

#### Modules: Hierarchy 模块：层次结构
- **Modules 模块**
- **Connecting Ports by Position 按位置连接端口**
- **Connecting Ports by Name 按名称连接端口**
- **Three Modules 三个模块**
- **Modules and Vectors 模块和向量**
- **Adder 1 加法器1**
- **Adder 2 加法器2**
- **Carry-Select Adder 选择进位加法器**
- **Adder-Subtractor 加法器-减法器**

---

#### Procedures 程序
程序包括 `always`、`initial`、`task` 和 `function` 块。程序允许使用顺序语句（这些语句不能在程序外使用）来描述电路的行为。

- **Always Blocks (Combinational) Always块（组合逻辑）**
- **Always Blocks (Clocked) Always块（时钟控制）**
- **If Statement If语句**
- **If Statement Latches If语句锁存器**
- **Case Statement Case语句**
- **Priority Encoder 优先编码器**
- **Priority Encoder with Casez 使用casez的优先编码器**
- **Avoiding Latches 避免锁存器**

---

#### More Verilog Features 更多Verilog特性
- **Conditional Ternary Operator 条件三元操作符**
- **Reduction Operators 缩减操作符**
- **Reduction: Even Wider Gates 缩减：更宽的门电路**
- **Combinational For-Loop: Vector Reversal 2 组合循环：向量翻转2**
- **Combinational For-Loop: 255-Bit Population Count 组合循环：255位人口计数**
- **Generate For-Loop: 100-Bit Binary Adder 2 生成循环：100位二进制加法器2**
- **Generate For-Loop: 100-Digit BCD Adder 生成循环：100位BCD加法器**

---

### Circuits 电路
#### Combinational Logic 组合逻辑
##### Basic Gates 基本门电路
- **Wire 导线**
- **GND 地线**
- **NOR Gate 或非门**
- **Another Gate 另一个门电路**
- **Two Gates 两个门电路**
- **More Logic Gates 更多逻辑门**
- **7420 Chip 7420芯片**
- **Truth Tables 真值表**
- **Two-Bit Equality 两位相等电路**
- **Simple Circuit A 简单电路A**
- **Simple Circuit B 简单电路B**
- **Combine Circuits A and B 组合电路A和B**
- **Ring or Vibrate? 铃声或振动？**
- **Thermostat 恒温器**
- **3-Bit Population Count 3位人口计数器**
- **Gates and Vectors 门电路和向量**
- **Even Longer Vectors 更长的向量**

---

##### Multiplexers 多路复用器
- **2-to-1 Multiplexer 2选1多路复用器**
- **2-to-1 Bus Multiplexer 2选1总线多路复用器**
- **9-to-1 Multiplexer 9选1多路复用器**
- **256-to-1 Multiplexer 256选1多路复用器**
- **256-to-1 4-Bit Multiplexer 256选1 4位多路复用器**

---

##### Arithmetic Circuits 算术电路
- **Half Adder 半加器**
- **Full Adder 全加器**
- **3-Bit Binary Adder 3位二进制加法器**
- **Adder 加法器**
- **Signed Addition Overflow 有符号加法溢出**
- **100-Bit Binary Adder 100位二进制加法器**
- **4-Digit BCD Adder 4位BCD加法器**

---

##### Karnaugh Map to Circuit 卡诺图到电路
- **3-Variable 3变量**
- **4-Variable 4变量**
- **Minimum SOP and POS 最小SOP和POS**
- **Karnaugh Map 卡诺图**
- **K-Map Implemented with a Multiplexer 用多路复用器实现的卡诺图**

---

#### Sequential Logic 时序逻辑
##### Latches and Flip-Flops 锁存器和触发器
- **D Flip-Flop D触发器**
- **D Flip-Flops 多个D触发器**
- **DFF with Reset 带复位的DFF**
- **DFF with Reset Value 带复位值的DFF**
- **DFF with Asynchronous Reset 带异步复位的DFF**
- **DFF with Byte Enable 带字节使能的DFF**
- **D Latch D锁存器**
- **DFF+DFF D触发器加门电路**
- **Mux and DFF 多路复用器和D触发器**
- **Detect an Edge 检测边沿**
- **Edge Capture Register 边沿捕捉寄存器**
- **Dual-Edge Triggered Flip-Flop 双边沿触发器**

---

##### Counters 计数器
- **Four-Bit Binary Counter 4位二进制计数器**
- **Decade Counter 十进制计数器**
- **Slow Decade Counter 慢速十进制计数器**
- **Counter 1-12 1-12计数器**
- **Counter 1000 1000计数器**
- **4-Digit Decimal Counter 4位十进制计数器**
- **12-Hour Clock 12小时制时钟**

---

##### Shift Registers 移位寄存器
- **4-Bit Shift Register 4位移位寄存器**
- **Left/Right Rotator 左/右旋转器**
- **Left/Right Arithmetic Shift 左/右算术移位**
- **5-Bit LFSR 5位线性反馈移位寄存器**
- **32-Bit LFSR 32位线性反馈移位寄存器**

---

##### More Circuits 更多电路
- **Cellular Automata 元胞自动机**
- **Rule 90 规则90**
- **Rule 110 规则110**
- **Conway's Game of Life 16x16 康威的生命游戏 16x16**

---

##### Finite State Machines 有限状态机
- **Simple FSM 简单有限状态机**
- **Design a Moore FSM 设计一个Moore FSM**
- **PS/2 Packet Parser PS/2包解析器**
- **Serial Receiver 串行接收器**
- **Sequence Recognition 序列识别**
- ...

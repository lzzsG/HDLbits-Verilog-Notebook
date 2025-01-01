---
layout: post
title: HDLbits Verilog Notebook
nav_order: 0
description: "HDLbits Verilog Notebook，HDLbits Verilog 笔记 目录"
permalink: /
---

# HDLbits Verilog Notebook

 HDLBits 是一个专注于使用 Verilog 硬件描述语言（HDL）进行数字硬件设计的小型电路设计练习平台，适合初学者和有一定经验的工程师学习数字逻辑设计。本笔记记录了在 HDLBits 平台上完成练习后的心得、解题思路和关键代码，旨在帮助学习者快速回顾与巩固 Verilog 的基础知识和模块化设计技巧。

### Contents 目录

1. **Getting Started 入门**
2. **Verilog Language Verilog语言**
   1. **Basics 基础**
   2. **Vectors 向量**
   3. **Modules: Hierarchy 模块：层次结构**
   4. **Procedures 程序**
   5. **More Verilog Features 更多Verilog特性**

---

### Getting Started 入门

- **Output Zero 输出为零**

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

#### More Verilog Features 更多Verilog特性

- **Conditional Ternary Operator 条件三元操作符**
- **Reduction Operators 缩减操作符**
- **Reduction: Even Wider Gates 缩减：更宽的门电路**
- **Combinational For-Loop: Vector Reversal 2 组合循环：向量翻转2**
- **Combinational For-Loop: 255-Bit Population Count 组合循环：255位人口计数**
- **Generate For-Loop: 100-Bit Binary Adder 2 生成循环：100位二进制加法器2**
- **Generate For-Loop: 100-Digit BCD Adder 生成循环：100位BCD加法器**

## Getting Started  
- [Getting Started](https://hdlbits.01xz.net/wiki/step_one) **入门**  
- [Output Zero](https://hdlbits.01xz.net/wiki/zero) **输出零**

## Verilog Language Verilog语言

### Basics 基础

- [Simple wire](https://hdlbits.01xz.net/wiki/wire) **简单导线**
- [Four wires](https://hdlbits.01xz.net/wiki/wire4) **四根导线**
- [Inverter](https://hdlbits.01xz.net/wiki/notgate) **反相器**
- [AND gate](https://hdlbits.01xz.net/wiki/andgate) **与门**
- [NOR gate](https://hdlbits.01xz.net/wiki/norgate) **或非门**
- [XNOR gate](https://hdlbits.01xz.net/wiki/xnorgate) **同或门**
- [Declaring wires](https://hdlbits.01xz.net/wiki/wire_decl) **声明导线**
- [7458 chip](https://hdlbits.01xz.net/wiki/7458) **7458芯片**

### Vectors 向量

- [Vectors](https://hdlbits.01xz.net/wiki/vector0) **向量**
- [Vectors in more detail](https://hdlbits.01xz.net/wiki/vector1) **详细解释向量**
- [Vector part select](https://hdlbits.01xz.net/wiki/vector2) **向量部分选择**
- [Bitwise operators](https://hdlbits.01xz.net/wiki/vectorgates) **按位操作符**
- [Four-input gates](https://hdlbits.01xz.net/wiki/gates4) **四输入门**
- [Vector concatenation operator](https://hdlbits.01xz.net/wiki/vector3) **向量连接操作符**
- [Vector reversal 1](https://hdlbits.01xz.net/wiki/vectorr) **向量翻转 1**
- [Replication operator](https://hdlbits.01xz.net/wiki/vector4) **复制操作符**
- [More replication](https://hdlbits.01xz.net/wiki/vector5) **更多复制**

### Modules: Hierarchy 模块：层次结构

- [Modules](https://hdlbits.01xz.net/wiki/module) **模块**
- [Connecting ports by position](https://hdlbits.01xz.net/wiki/module_pos) **按位置连接端口**
- [Connecting ports by name](https://hdlbits.01xz.net/wiki/module_name) **按名称连接端口**
- [Three modules](https://hdlbits.01xz.net/wiki/module_shift) **三个模块**
- [Modules and vectors](https://hdlbits.01xz.net/wiki/module_shift8) **模块和向量**
- [Adder 1](https://hdlbits.01xz.net/wiki/module_add) **加法器 1**
- [Adder 2](https://hdlbits.01xz.net/wiki/module_fadd) **加法器 2**
- [Carry-select adder](https://hdlbits.01xz.net/wiki/module_cseladd) **选择进位加法器**
- [Adder-subtractor](https://hdlbits.01xz.net/wiki/module_addsub) **加法器-减法器**

### Procedures 程序

程序包括 **always** 块、initial 块、task 和 function 块。程序允许使用顺序语句（这些语句不能在程序外使用）来描述电路的行为。

- [Always blocks (combinational)](https://hdlbits.01xz.net/wiki/alwaysblock1) **组合逻辑的 Always 块**
- [Always blocks (clocked)](https://hdlbits.01xz.net/wiki/alwaysblock2) **时钟控制的 Always 块**
- [If statement](https://hdlbits.01xz.net/wiki/always_if) **If 语句**
- [If statement latches](https://hdlbits.01xz.net/wiki/always_if2) **If 语句锁存器**
- [Case statement](https://hdlbits.01xz.net/wiki/always_case) **Case 语句**
- [Priority encoder](https://hdlbits.01xz.net/wiki/always_case2) **优先编码器**
- [Priority encoder with casez](https://hdlbits.01xz.net/wiki/always_casez) **带 casez 的优先编码器**
- [Avoiding latches](https://hdlbits.01xz.net/wiki/always_nolatches) **避免锁存器**

### More Verilog Features 更多 Verilog 特性

- [Conditional ternary operator](https://hdlbits.01xz.net/wiki/conditional) **条件三元操作符**
- [Reduction operators](https://hdlbits.01xz.net/wiki/reduction) **缩减操作符**
- [Reduction: Even wider gates](https://hdlbits.01xz.net/wiki/gates100) **缩减：更宽的门**
- [Combinational for-loop: Vector reversal 2](https://hdlbits.01xz.net/wiki/vector100r) **组合 for 循环：向量翻转 2**
- [Combinational for-loop: 255-bit population count](https://hdlbits.01xz.net/wiki/popcount255) **组合 for 循环：255 位人口计数**
- [Generate for-loop: 100-bit binary adder 2](https://hdlbits.01xz.net/wiki/adder100i) **生成 for 循环：100 位二进制加法器 2**
- [Generate for-loop: 100-digit BCD adder](https://hdlbits.01xz.net/wiki/bcdadd100) **生成 for 循环：100 位 BCD 加法器**



## Circuits 电路

### Combinational Logic 组合逻辑

#### Basic Gates 基本门电路

- [Wire](https://hdlbits.01xz.net/wiki/exams/m2014_q4h) **导线**
- [GND](https://hdlbits.01xz.net/wiki/exams/m2014_q4i) **地线**
- [NOR](https://hdlbits.01xz.net/wiki/exams/m2014_q4e) **或非门**
- [Another gate](https://hdlbits.01xz.net/wiki/exams/m2014_q4f) **另一个门**
- [Two gates](https://hdlbits.01xz.net/wiki/exams/m2014_q4g) **两个门**
- [More logic gates](https://hdlbits.01xz.net/wiki/gates) **更多逻辑门**
- [7420 chip](https://hdlbits.01xz.net/wiki/7420) **7420芯片**
- [Truth tables](https://hdlbits.01xz.net/wiki/truthtable1) **真值表**
- [Two-bit equality](https://hdlbits.01xz.net/wiki/mt2015_eq2) **两位相等**
- [Simple circuit A](https://hdlbits.01xz.net/wiki/mt2015_q4a) **简单电路 A**
- [Simple circuit B](https://hdlbits.01xz.net/wiki/mt2015_q4b) **简单电路 B**
- [Combine circuits A and B](https://hdlbits.01xz.net/wiki/mt2015_q4) **组合电路 A 和 B**
- [Ring or vibrate?](https://hdlbits.01xz.net/wiki/ringer) **振铃或振动**
- [Thermostat](https://hdlbits.01xz.net/wiki/thermostat) **恒温器**
- [3-bit population count](https://hdlbits.01xz.net/wiki/popcount3) **3 位人口计数**
- [Gates and vectors](https://hdlbits.01xz.net/wiki/gatesv) **门电路和向量**
- [Even longer vectors](https://hdlbits.01xz.net/wiki/gatesv100) **更长的向量**

#### Multiplexers 多路复用器

- [2-to-1 multiplexer](https://hdlbits.01xz.net/wiki/mux2to1) **2选1多路复用器**
- [2-to-1 bus multiplexer](https://hdlbits.01xz.net/wiki/mux2to1v) **2选1总线多路复用器**
- [9-to-1 multiplexer](https://hdlbits.01xz.net/wiki/mux9to1v) **9选1多路复用器**
- [256-to-1 multiplexer](https://hdlbits.01xz.net/wiki/mux256to1) **256选1多路复用器**
- [256-to-1 4-bit multiplexer](https://hdlbits.01xz.net/wiki/mux256to1v) **256选1 4位多路复用器**

#### Arithmetic Circuits 算术电路

- [Half adder](https://hdlbits.01xz.net/wiki/hadd) **半加器**
- [Full adder](https://hdlbits.01xz.net/wiki/fadd) **全加器**
- [3-bit binary adder](https://hdlbits.01xz.net/wiki/adder3) **3位二进制加法器**
- [Adder](https://hdlbits.01xz.net/wiki/exams/m2014_q4j) **加法器**
- [Signed addition overflow](https://hdlbits.01xz.net/wiki/exams/ece241_2014_q1c) **有符号加法溢出**
- [100-bit binary adder](https://hdlbits.01xz.net/wiki/adder100) **100位二进制加法器**
- [4-digit BCD adder](https://hdlbits.01xz.net/wiki/bcdadd4) **4位 BCD 加法器**

#### Karnaugh Map to Circuit 卡诺图到电路

- [3-variable](https://hdlbits.01xz.net/wiki/kmap1) **3变量**
- [4-variable](https://hdlbits.01xz.net/wiki/kmap2) **4变量**
- [4-variable](https://hdlbits.01xz.net/wiki/kmap3) **4变量**
- [4-variable](https://hdlbits.01xz.net/wiki/kmap4) **4变量**
- [Minimum SOP and POS](https://hdlbits.01xz.net/wiki/exams/ece241_2013_q2) **最小 SOP 和 POS**
- [Karnaugh map](https://hdlbits.01xz.net/wiki/exams/m2014_q3) **卡诺图**
- [Karnaugh map](https://hdlbits.01xz.net/wiki/exams/2012_q1g) **卡诺图**
- [K-map implemented with a multiplexer](https://hdlbits.01xz.net/wiki/exams/ece241_2014_q3) **用多路复用器实现的卡诺图**

### Sequential Logic 时序逻辑

#### Latches and Flip-Flops 锁存器和触发器

- [D flip-flop](https://hdlbits.01xz.net/wiki/dff) **D 触发器**
- [D flip-flops](https://hdlbits.01xz.net/wiki/dff8) **多个 D 触发器**
- [DFF with reset](https://hdlbits.01xz.net/wiki/dff8r) **带复位的 DFF**
- [DFF with reset value](https://hdlbits.01xz.net/wiki/dff8p) **带复位值的 DFF**
- [DFF with asynchronous reset](https://hdlbits.01xz.net/wiki/dff8ar) **带异步复位的 DFF**
- [DFF with byte enable](https://hdlbits.01xz.net/wiki/dff16e) **带字节使能的 DFF**
- [D Latch](https://hdlbits.01xz.net/wiki/exams/m2014_q4a) **D 锁存器**
- [DFF](https://hdlbits.01xz.net/wiki/exams/m2014_q4b) **D 触发器**
- [DFF](https://hdlbits.01xz.net/wiki/exams/m2014_q4c) **D 触发器**
- [DFF+gate](https://hdlbits.01xz.net/wiki/exams/m2014_q4d) **D 触发器和门电路**
- [Mux and DFF](https://hdlbits.01xz.net/wiki/mt2015_muxdff) **多路复用器和 D 触发器**
- [Mux and DFF](https://hdlbits.01xz.net/wiki/exams/2014_q4a) **多路复用器和 D 触发器**
- [DFFs and gates](https://hdlbits.01xz.net/wiki/exams/ece241_2014_q4) **D 触发器和门电路**
- [Create circuit from truth table](https://hdlbits.01xz.net/wiki/exams/ece241_2013_q7) **根据真值表创建电路**
- [Detect an edge](https://hdlbits.01xz.net/wiki/edgedetect) **检测边沿**
- [Detect both edges](https://hdlbits.01xz.net/wiki/edgedetect2) **检测双边沿**
- [Edge capture register](https://hdlbits.01xz.net/wiki/edgecapture) **边沿捕获寄存器**
- [Dual-edge triggered flip-flop](https://hdlbits.01xz.net/wiki/dualedge) **双边沿触发器**

#### Counters 计数器

- [Four-bit binary counter](https://hdlbits.01xz.net/wiki/count15) **4位二进制计数器**
- [Decade counter](https://hdlbits.01xz.net/wiki/count10) **十进制计数器**
- [Decade counter again](https://hdlbits.01xz.net/wiki/count1to10) **十进制计数器再现**
- [Slow decade counter](https://hdlbits.01xz.net/wiki/countslow) **慢速十进制计数器**
- [Counter 1-12](https://hdlbits.01xz.net/wiki/exams/ece241_2014_q7a) **1-12 计数器**
- [Counter 1000](https://hdlbits.01xz.net/wiki/exams/ece241_2014_q7b) **1000 计数器**
- [4-digit decimal counter](https://hdlbits.01xz.net/wiki/countbcd) **4位十进制计数器**
- [12-hour clock](https://hdlbits.01xz.net/wiki/count_clock) **12小时制时钟**

#### Shift Registers 移位寄存器

- [4-bit shift register](https://hdlbits.01xz.net/wiki/shift4) **4位移位寄存器**
- [Left/right rotator](https://hdlbits.01xz.net/wiki/rotate100) **左右旋转器**
- [Left/right arithmetic shift by 1 or 8](https://hdlbits.01xz.net/wiki/shift18) **左右算术移位 1 位或 8 位**

- [5-bit LFSR](https://hdlbits.01xz.net/wiki/lfsr5) **5位线性反馈移位寄存器**
- [3-bit LFSR](https://hdlbits.01xz.net/wiki/mt2015_lfsr) **3位线性反馈移位寄存器**
- [32-bit LFSR](https://hdlbits.01xz.net/wiki/lfsr32) **32位线性反馈移位寄存器**
- [Shift register](https://hdlbits.01xz.net/wiki/exams/m2014_q4k) **移位寄存器**
- [Shift register](https://hdlbits.01xz.net/wiki/exams/2014_q4b) **移位寄存器**
- [3-input LUT](https://hdlbits.01xz.net/wiki/exams/ece241_2013_q12) **3输入查找表（LUT）**

#### More Circuits 更多电路

- Cellular automata **元胞自动机**
  - [Rule 90](https://hdlbits.01xz.net/wiki/rule90) **规则90**
  - [Rule 110](https://hdlbits.01xz.net/wiki/rule110) **规则110**
  - [Conway's Game of Life 16x16](https://hdlbits.01xz.net/wiki/conwaylife) **康威生命游戏 16x16**




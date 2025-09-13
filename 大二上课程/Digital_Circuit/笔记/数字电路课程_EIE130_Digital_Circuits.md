# 数字电路课程 EIE130 Digital Circuits

## 2025.9.4

### Chapter1 Digital system and information

####  Analog Quantities

most natural quantities that we see are analog(模拟) and vary continuously. Analog system can generally handle higher power than digital system

- 譬如大哥大，就是通过直接传播声音，会有噪声，这就是模拟信号
- 现在的电话和微信语音是通过算法把声音转化(压缩)成信号，然后发送过去，这个算法是digital的

所以我们尝试将analog信号转化成digital信号（通过抽样 $T_s= \dfrac{1}{F_s}$ ，根据香农定理，需要抽样最大频率的两倍），通过low-pass-filter（低通滤波器），恢复原来的analog信号，最简单的低通滤波器就是RC circuit

> CD光盘播放的时候，可能会脏，但是还是可以比较正常播放，因为有纠错机制[BCH和RS（所罗门）]

#### Types of Digital System

1. No state present (input = output) state可以理解成可以储存东西

2. state present
    1.  state update at discrete time(有clock)-->Synchronous Sequential System
    2. state update at any time -->Asynchronous Sequential System

#### Digtal System Example

里程表，每加一都是从当前的数目加1，显示储存了上一个的数据，所以是sequential system

电脑，

#### Embedded Computer(嵌入式)

computers as intergral parts of other products

#### Information Representation-Signal

digit 0 and 1 (bit = binary digit) 1 byte = 8bit

#### Signal Example Over Time

Analog : Continuous in value & time

Asynchronous: Discrete in value & continuous in 

#### Pulse Definition

Overshoot：冲击上去，最高的，比较有用，稳定的电路overshoot要低

#### Periodic Pulse Waveforms

 $T= \dfrac{1}{F}$ herts

 Periodic pulse waveforms are composed of pulses that repeats  in a fixed interval called the period (second). The frequency is  the rate it repeats and is measured in hertz (Hz)(赫兹是每秒钟震动的次数).

#### Timing Diagram

几个电路在时间下的关系

A diagram like this can be observes directly on a logic analyzer

#### Signal and Parallel Data

- serial transfer (并行)

- parallel transfer(串行)

虽然并行传输快，但是容易出错，用串行

> 最典型的串行是USB

#### Basic Logic Function

AND: all are true

OR: true only if one or more input conditions are true

NOT: Indicate the opposite condition

comparision function: 两个数比较，大于等于是0

> CPU 为了简化比较器，使用两个数相减，负数直接去除

arithmetic functions

- encoding function（编码）复杂的输入变成简单的输出

譬如输入9，输出1001

- decoding function（解码）简单的输入变成复杂的输出

譬如输入0011，输出3

multiplexer: 多路选择器

counting function: 计数器

register: 寄存器

shift register: 移位寄存器

#### Intergrate Circuit

DIP封装

#### Test and Measurement Instrument

可以检测数字电路或模拟电路

#### Programing Logic Device

#### Traditional Digital System --> Irreversible(不可逆：很难从输出找到输入)

信息丢失会产生heat eg. cpu可以达到100度

#### A reversible digital system

理论上可逆的电路不会损耗电路

做出reversible的系统，需要做出reversible gate

Logic Synthesis theory 线合理论，可以作出可逆门

#### Number System-Representation

Radix/base 基： 不同位置对应不同基

#### Commonly Occurring Bases

0,1给机器用的

0,1,2,3,4,5,6,7,8,9是给人用的

8位计数是为了减少二进制的储存

#### Digital Numbers

#### Negatibe Position Number

#### Binary Conversion Example

**算二进制的时候**：整数用除，小数用乘

## 2025.9.11

- **BCD码**： 8421码

- 二进制看到2进位

- 乘法就是AND gate

    $0\times 0 = 0 1	$

- 补码：求反加1，用来表示负数，可以化成$A - B = A + (-B)$ 

- 正数加0，负数加1
- **overflow 溢出**：不够存答案
    - 譬如正数加正数得到负数
    - 负数加负数得到正数

- **gray code**： 前后相差一位的码
    - **ASCII** 	

## Chapter 2


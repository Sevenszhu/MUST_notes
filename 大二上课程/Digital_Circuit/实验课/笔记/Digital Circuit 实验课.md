# Digital Circuit 实验课

PLD 可编程控件

ISP 在系统可编程（就是可以通过后续编程）

## 1032E

- 有6000个门，门越多越可以模拟越复杂的试验
- I/O input and output ：只能64个
- 只可以储存192bit （192 register）
- working frequency = 125 MHz 
- TTL : 5V 是high = 1 其他都是low = 0
- 四个时钟
- 2个output enable ，如果是disable的话，就会将自己变成很大的电阻，就会隔离开芯片
- Global Routing Pool 全局布线区

最重要就是四种file，记住后复制他们，可以自动生产其他文件

点的时候

1. Show Obsolete Devices
2. Family: ispLSI 1K Devices
3. Device: ispLS1032E
4. Speed.grade:MH2: 70
5. Package type: B4PLCC
6. Part Name: ispLS11032E-70LJ84

- ariths.lib 全/半加
- gates.lib 门
- iopads.lib 引脚
- muxes.lib 多样选择器

## ABEL语言

​	

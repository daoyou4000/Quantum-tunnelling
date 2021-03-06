# Quantum-tunnelling
In this folder I would like to note down my understanding of the Quantum tunneling and why it affects the chip manufacturing. 

## 10nm 工艺制程

10nm 指的是尺度，半导体是基于硅基底，通过微纳加工制造微型化的电子元器件。10nm 是指最小可以在这个尺度上制备出基本元器件。

在半导体制程中，如果工艺制程越小则意味着芯片上的三极管越小。
## 场效应管
我们假设三极管或者场效应管是芯片上的最小单位控制着高低电平的翻转等。

![N-Channel MOSFET Structure](https://github.com/daoyou4000/Quantum-tunnelling/blob/main/image/N-Channel.PNG "N-Channel MOSFET Structure")

如上图所示，N沟道场效应管的结构示意图，当在GS 施加正向电压时，形成N沟道。
![image](https://github.com/daoyou4000/Quantum-tunnelling/blob/main/image/N-Channel-On.PNG "N-Channel ON")

下图描述了GS 和DS 之间电压的与电流之间的曲线
![image](https://github.com/daoyou4000/Quantum-tunnelling/blob/main/image/Curve.PNG)

## 为什么制程越小会产生量子隧穿

由以上几个图片可知，当制程越小时意味着沟道的长度越短，那么由于量子隧穿效应，电子有可能在没有施加电场时产生电流并且改变电平(不确定)。
此时就会影响芯片的计算或者存储的精确性。

## Reference 
- [MOSFET Introduction](https://zhuanlan.zhihu.com/p/53643465)
- [Quantum tunnelling](https://en.wikipedia.org/wiki/Quantum_tunnelling)

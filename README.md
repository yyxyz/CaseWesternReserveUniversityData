# [CaseWesternReserveUniversityData](http://csegroups.case.edu/bearingdatacenter/home)

## Project History

为了验证新的技术、理论，常常需要实验。这些电机轴承实验被进行是为了取得IQ PreAlert（一个由Rockwell开发的电机轴承状态评估系统）的性能特征。从这一项目进行以来，获取了一系列可以用来验证或改进电机性能评价技术的电机性能数据库。一些已经或正在利用这些数据库的项目包括：Winsnode状态评估技术，基于模型的诊断技术，电机转速确定算法。

## 设备 & Procedures

如图1所示，实验平台包括一个2马力的电机（左侧），一个转矩传感器（中间），一个功率计（右侧）和电子控制设备（没有显示）。被测试轴承支承电机轴。使用电火花加工技术在轴承上布置了单点故障，故障直径分别为0.007、0.014、0.021 mils、0.028 mils和0.040英寸(1厘米=0.001 英寸)。See FAULT SPECIFICATIONS for fault depths.其中前三种故障直径的轴承使用的是SKF轴承，后两种故障直径的轴承使用的是与之等效的NTN轴承。主动端轴承和fan end bearing specifications, including bearing geometry and defect frequencies are listed in the BEARING SPECIFICATIONS.

实验中使用加速度采集振动信号，通过使用磁性底座将传感器安放在电机壳体上。加速度传感器分别安装在电机壳体的驱动端12点钟的位置。在有些实验中，传感器也被安放在电机支承底盘上。振动信号是通过16通道的DAT记录器采集的，并且后期在MATLAB环境中处理。数字信号的采样频率为12000Hz，驱动端轴承故障数据同时也以48000Hz的采样速率采集。 Speed and horsepower data were collected using the torque transducer/encoder and were recorded by hand.

外圈的故障是固定不变的，因此故障相对于轴承受载区域的位置对电机/轴承系统的振动响应由直接的影响。为了对这个影响进行定量研究，实验中分别对驱动和风扇端的轴承外圈布置3点钟（直接位于受载区）、6点钟（正交于受载区）、12点钟方向的故障。

## 下载数据文件

共采集了正常轴承、单点驱动端和风扇端故障的数据。对于驱动端轴承，分别使用12kHz和48kHz的频率来进行了数据的采集。对于风扇端轴承，仅仅使用12kHz的频率进行了数据的采集。 
数据文件均为Matlab格式（.mat格式）。每一个文件包含了风扇端和驱动端振动数据，也包含了电机转速。对于所有的文件，变量名字的含义如下： 
DE - 驱动端加速度数据 
FE - 风扇端加速度数据 
BA - 基本加速度数据 
time - 时间序列数据 
RPM- rpm during testing



Click on a link below to continue:

- [Normal Baseline Data](http://csegroups.case.edu/bearingdatacenter/pages/normal-baseline-data)
- [12k Drive End Bearing Fault Data](http://csegroups.case.edu/bearingdatacenter/pages/12k-drive-end-bearing-fault-data)
- [48k Drive End Bearing Fault Data](http://csegroups.case.edu/bearingdatacenter/pages/48k-drive-end-bearing-fault-data)
- [Fan-End Bearing Fault Data](http://csegroups.case.edu/bearingdatacenter/pages/12k-fan-end-bearing-fault-data)

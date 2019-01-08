# M2：[数据输出](https://github.com/OS-Q/M2) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属控制体系：[Q1](https://github.com/OS-Q/Q1)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M2/wiki) 

M2数据输出节点，用于对外输出控制，实现系统的数据消费过程

### [共用资源](OS-Q/) 

#### [数据处理](IO/)

包括串口数据的收发格式

#### [归一化层](OS-Q/)

平台开发的归一化接口文件

---

- 边缘设备命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含平台](https://github.com/OS-Q/M2/wiki) 

#### W5：[比特输出](https://github.com/OS-Q/W5)

比特逻辑输出，包括开关状态控制

#### W6：[字节输出](https://github.com/OS-Q/W6)

连续量输出，对外设器件数字输出

#### W7：[显示输出](https://github.com/OS-Q/W7)

连接显示设备，驱动显示相关信息

#### W8：[空间输出](https://github.com/OS-Q/W8)

通过驱动装置实现空间位置输出

#### W9：[其他输出](https://github.com/OS-Q/W9)

其他内容输出方式

## [同级节点](https://github.com/OS-Q/Q1/wiki)

#### M1：[信号采集](https://github.com/OS-Q/M1)

控制外接信号输入，完成数据采集过程

#### [M2：数据输出](https://github.com/OS-Q/M2)

控制对外信号输出，完成数据消费过程

#### M3：[闭环控制](https://github.com/OS-Q/M3)

集成相关资源，组合完成预定闭环控制


---

####  © qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  @ 2018-12-11

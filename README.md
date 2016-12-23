# stlink-uart
串口和stlink/V2二合一调试工具。

---
3d模型图
![image](https://github.com/solosky/stlink-uart/raw/master/preview/PCB_3d_Top.png)
![image](https://github.com/solosky/stlink-uart/raw/master/preview/PCB_3d_Bottom.png)
USB设备树
![image](https://github.com/solosky/stlink-uart/raw/master/preview/USB设备树.png)
接口定义
![image](https://github.com/solosky/stlink-uart/raw/master/preview/接口定义.png)

方案：
 * GL852G - USB HUB
 * CP2102 - UART USB Bridge
 * STM32F103C8T6 - STLINK/V2

支持的功能：
 * SWIM 编程和调试（STM8）
 * SWD 编程和调试（stm32/ARM系列）
 * UART（导出DTR，支持arduino一键下载）
 * 3.3V提供最大500mA电流，可以作为调试目标的电源输出
 * 电源/tx/rx/stlink指示灯
 * MicroUSB 或者 标准USB A型
 
 
# 开源协议
本编程器是基于apache Lisence 2.0 开源协议发布，允许商业使用或修改包括源代码和PCB，而无需经过我的授权。
但是请保留署名作者的权利。
如果在商业使用了本编程器的任何源代码和PCB内容，恕不提供技术支持，抱歉。
但如果能告知我使用了我的设计，我会感到很高兴的。

# 瑞奥的测试


- 学习串口工具的使用、AT简单指令集、协议报文
- 调试微型站数据出现数据不完整现象，LoRaWan协议图如下：


![LoraWan](_images/1.jpg)



- 测试过程
  - VOC发送数据到PC，SSCOM收集数据，统计数据完整性百分比；
  - PC通过SSCOM向DTU发送数据，经过LoRaWAN网关和Loriot第三方平台采集数据，通过日志统计数据完整性百分比


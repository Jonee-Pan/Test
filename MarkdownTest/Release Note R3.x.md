# WSOP.RDA8955 SDK Release Note #
---
   

### WSOP.RDA8955\_SDK\_R3.10.1549\_20191025 ###
1. 完善对接阿里云平台的MQTT示例代码。   
2. **增加PS FOTA的API**。   
3. 增加获取网络信号质量的API、获取SIM卡状态的API。   
4. 更新NV API的使用注意事项。   
5. 优化Audio API，以及示例代码。   
6. 优化SIM和network 部分API。   
   
----------
### WSOP.RDA8955\_SDK\_R3.9.1515\_20190929 ###
1. 修改音频播放API文档，以及示例代码。   
2. 增加 sample\_app\_f8\_tts 示例target，用于F8硬件，并支持TTS功能。   
3. TTS播放示例增加设置音量。   
4. 增加获取版本号接口。   
   

----------
### WSOP.RDA8955\_SDK\_R3.7.1433\_20190815 ###
1. 修改TLS连接接口，支持IPV6。
2. 修改TTS播放示例。
3. 增加RTC闹钟API。
4. 增加获取开机原因接口。
5. 增加UDP demo code、fix NV demo code。
6. 增加TTS全异步播放的API 以及响应的示例代码。

----------
### WSOP.RDA8955\_SDK\_R3.5.1376\_20190508 ###
1. 添加数字运算相关API。
2. 完善socket、tls示例代码。
3. 增加音频接口CZ_AudioGetDurationTime，CZ_AudioFileOffsetPlay，CZ_AudioBufferPlay。
4. 增加读取、写入APP升级文件名接口。
5. 修复特定文件加载内容失败的问题。
6. 修改CZ_GetIpByName()第二个参数的数据结构。
7. 增加IPV6连接接口。
8. 修改wsop_app.ld，修复部分bbs段没有清0的问题。
9. 在编译链接阶段引入内存越界检测。
10. GPIO配置增加高阻态。

----------
### SDK版本：WSOP.RDA8955\_SDK\_R3.0.1294\_20190128 ###
### 对应的底包固件版本号必须是 <product>_2.2.xx.xx_201901xx_R 以上的 ###
1. SDK R3.x与R2.x不兼容，但是代码层面的API是兼容的，就是说，要使用R3.0的SDK，必须重新使用SDK编译WSOP APP。
2. 文件系统由SPIFFS变更为SFFS。
3. 增加PWT（受限的PWM） API。

----------
### WSOP.RDA8955\_SDK\_R2.2.1057\_20180724 ###
1. 增加获取tickCout的接口;
2. 修改CZ_NvAppInfoRead接口
3. 增加TTS相关API；
4. 增加TTS示例及说明文档；
5. SDK编译增加区分4M或8M的FLASH；
6. 实现通过VBAT获取电池电量；
7. 示例增加获取电池电量测试；

----------
### WSOP.RDA8955\_SDK\_R2.1.811\_20180419 ###
1. 增加腾讯云鉴权接口；
2. 当前服务小区信息增加接收信号质量、接收电平最小值、定时提前等；
3. 增加GPIO配置上/下拉接口；
4. 增加添加新项目、SOCKET、UART、GPIO示例的流程说明。

----------
### WSOP.RDA8955\_SDK\_R2.0.671\_20180330 ###
1. 修改串口配置：增加UART1的配置；
2. 增加I2C读写原始数据接口，对非标准的I2C用法进行访问；
4. 添加保存NV的接口：
5. 添加NV API说明文档及demo；
6. 增加电源控制接口:CZ_EnablePower()

----------
### WSOP.RDA8955\_SDK\_R2.0.557\_20180313 ###
1. 初始版本；
# Opencore-for-HP-23-q072cn-AIO
opencore for HP aio 23-q072cn



这是一个用于惠普Pavillion 23-q072cn一体机台式电脑的Opencore集成。



机器配置如下：

Haswell平台：i7-4785T

图形计算运行在核心显卡上:HD4600

支援H264(avc)的硬件加速编解码

构建在itlwm上的英特尔网络调制解调器:Intel wireless AC 3160

Realtek的有线网络适配器

8GB 1600Mhz DDR3内存



注意⚠️：测试时运行在外置的Samsung T5 移动硬盘上，以取得较为理想的速度



正在工作：

Monterey 12.2

背光亮度调节

通过usb连接的内置hp网络摄像头

麦克风、扬声器以及3.5mm模拟信号输出

所有USB接口

大部分功能



无法工作：

板载独立显卡AMD Radeon A360（该显卡为移动端显卡马甲，无独立vbios组件，无法支持编解码单元，已禁用）

i don't know, you tell me



基于开源组件

﻿
2018.3.1
1.完成8位和16位磁导航传感器设计
2.增加log日志文件

2018.2.28
1.Dbus增加实时帧,无响应模式,速度更快,适用于传感器数据上传
2.Dbus功能完成
3.需要增加通信接口：OPC和Profinet

2018.1.30
1.主窗体和配置页面之间增加消息委托，连接状态变化时自动通知主窗体
--------
1.实现AGV列表自动更新，双击AGV下的寄存器弹出编辑框

问题：同时只能弹出一个设备的编辑框(已修复2018.1.31)

2018.1.31
1.修复2018.1.30遗留问题
2.定义AGV类，AGV列表依据AGV类自动扩展
3.增加AGV列表子菜单图标
4.优化寄存器列表及单个寄存器Form中的变量
5.更改dbus协议，增加头和尾，单向调试完成

2018.2.1
1.努力解决数解析问题中

2018.2.2
1.通信格式改为字符串通信，利用缓冲池机制，增加消息头和消息尾
2.编码及解码完成

2018.2.11
1.dbus所有功能完成，等待测试

2018.2.22
1.解析心跳  OK
1.写单个寄存器  发送等待结果时界面会卡，需要增加线程

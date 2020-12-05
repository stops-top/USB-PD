# [PD](https://github.com/Qful/PD)

[![sites](http://182.61.61.133/link/resources/Qful.png)](http://www.Qful.net)
## [项目简介](https://github.com/Qful/PD)

[PD](https://github.com/Qful/PD)(PowerDelivery) 充电协议是USB-IF组织公布的功率传输协议，它可以使目前默认最大功率5V/2A的type-c接口提高到100W，同时谷歌宣布Android7.0以上的手机搭载的快充协议必须支持PD协议。

传统的Micro USB 2A电流上限意味着无法再通过提高电流实现更高功率传输。USB-PD在谷歌的推动下已经收编了高通的QC快充协议。

USB-PD关注的是两个或者多个设备，甚至是基于USB接口的智能电网的电能传输过程，电能传输可以是双方向的，甚至是组网的，可以具备系统级供电策略。

USB-PD的通信是将协议层的消息调制成24MHZ的FSK信号并耦合到VBUS上或者从VBUS上获得FSK信号来实现手机和充电器通信的过程。

USB-PD快充协议是以 Type-C 接口作为物理载体输出的，但Type-C接口不一定都支持USB-PD协议。

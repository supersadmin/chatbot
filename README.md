# ChatBot 聊天机器人

一个功能简单、稳定的聊天机器人.  
你可以通过该机器人接入一些有趣的 API 来实现一些好玩的应用,例如快递查询、毒鸡汤、斗图等,也可以把自己人接入自己的服务中,作为告警、定时通知等服务.

## 接入流程

![流程图](./images/flow.png)

> 图上蓝色部分都是你需要做的内容

## 具体步骤

1. 添加机器人为好友,一般在 1-2 分钟后会自动通过
2. 根据提示操作,可以发送#帮助#来获取具体指令,激活和绑定机器人
3. 编写代码,连接机器人的 WebSocket Server 用于接收推送消息
4. 编写 Http Client 的代码,用于请求机器人接口,让机器人发送消息给你  
   这里有几个不同语言的简单 demo 可以参考
    - [ChatBot-Go]()
    - [ChatBot-NodeJS]()
    - [ChatBot-PHP]()

## 示例截图

![demo1](./images/demo1.png) ![demo2](./images/demo2.png)

## 联系方式

#### 机器人微信

#### 技术交流群

![qrcode_group](./images/qrcode_group.png)

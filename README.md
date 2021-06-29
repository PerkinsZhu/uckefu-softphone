#UCKeFu-SoftPhone
        SoftPhone是一款基于 FreeSWITCH 的 Web软电话工具条产品，纯Javascript，支持IE10以上浏览器，支持坐席账号登陆/登出功能、呼入呼出、就绪/未就绪、挂起/取回、咨询、转接、会议等功能，可以通过Web界面进行呼入呼出工作，功能完备，坐席能够通过SoftPhone界面完成全部工作流程。

         **SoftPhone是目前市场上唯一一款提供Web语音通信功能的开源软电话产品（无需软硬话机即可通话）** 

 **接入FreeSwitch配置：** 


1. 修改UCKeFu-SoftPhone\assets\js\UKeFu-SoftPhone.js文件中的FreeSwitch地址和端口：

    var ws_address = "192.168.3.11" , ws_port = "5066" ;

1. 保存修改
1. 访问index.html，点击工具条中的“登陆”按钮
1. 输入分机号和密码后登陆


 **注：FreeSwitch需要开启 5066 的WebSocket端口** 

美图如下：
![输入图片说明](https://git.oschina.net/uploads/images/2017/0420/082519_6c67b9d6_1200081.png "在这里输入图片标题")








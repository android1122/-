# 网易签到
网易考拉签到
使用方式：修改py文件的用户名和密码即可

逻辑：使用微博的第三方登录模块登录到网易考拉，然后自动签到，获取考拉豆

问题：1，国外vps使用这个的话，会触发微博的验证码，导致无法登录

后期：
1，将其改为class类，方便后续开发
2，验证码问题解决，要么使用开源的辨别库，要么使用发送邮件链接给用户，由用户手工填写。

这是无聊至极写的一个小程序，全部使用request库，主要让自己熟悉request库。有什么建议欢迎提出，

最后，网易鸡贼的将网页签到改成了app签到，目前来看，似乎是没办法继续使用，仅保留纪念吧

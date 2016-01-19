# 云客服系统-Gmail配置指南

标签（空格分隔）：云客服系统 Email

---

> 添加邮箱账号

- 发送协议: smtp
- 发送服务器: smtp.gmail.com
- 发送端口: 465
- 接收协议: imaps
- 接收服务器: imap.gmail.com
- 接收端口:993

> 设置用户和邮箱关联

将邮箱设置到对应的ERP账号上

> 设置邮件标签

- 过滤邮件: 
是 : 符合过滤器要求的邮件将**不会**导入到ERP中
- 优先级
同一平台下, 为标签设置不同的优先级. 如果有邮件符合多个标签, 取优先级别最高的一个.

> Gmail客户端设置

1. Gmail设置里要允许imap协议
![gmail启用IMAP][1]


2. [google账号设置][2] [链接地址](https://myaccount.google.com/security?hl=zh_CN&pli=1)
![google账号设置][5]

3. 点击图片中链接, 并选择【继续】[链接地址](https://accounts.google.com/DisplayUnlockCaptcha)
![此处输入图片的描述][6]


[1]: http://192.168.0.98/uploads/ckeditor/20150303163600180.png
[2]: httaccounts.google.com
[3]: http://192.168.0.98//uploads/ckeditor/20150303163836312.png
[4]: http://192.168.0.98/uploads/ckeditor/20150312103930588.png
[5]: http://192.168.0.98/uploads/ckeditor/20150703170850235.png
[6]: http://192.168.0.98/uploads/ckeditor/attachment/20150909112846520.png

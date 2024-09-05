# 账号以及使用

此文章为完全交付，其他后续则需要进一步商讨，至此本次项目结束。

### Github（源代码端）

Github账户名：imxieai
密码：xieai-114514

### Outlook邮箱

Outlook账户名：imxieai@outlook.com
密码：同GitHub

### Vercel（前后端搭建）

Vercel使用Github授权登录即可。
请注意，此处需要学习使用。

1. 登入Github
2. 访问Vercel
3. 使用Github登入，如下图
   ![vercel1](https://i.gyazo.com/96728e02b9aa61251836d588e3634522.png)
   
4. 登入后界面如下，点击Xieai5. 打开后，点击上方的Settings → Domains → 先在图片1处输入[随机字母].xieai.top加入一个新域名 → 在图片2处删除原有域名以实现防止有人单次付款多次使用（删除方法，点击edit → remove）
   ![vercel3](https://i.gyazo.com/d9498dccf46190aac79879b1b332e364.png)
   
5. 登入endless，具体步骤请继续阅读

### EndlessHost

网址：[Endless文件页](https://da.theendlessweb.com:2222/CMD_FILE_MANAGER?path=/domains/xieai.top/public_html/verify)
Endless为前端的实现虚拟主机
使用的免费版，账户名：imxieai1
密码：ZHj]E8O,n>a/

6. 登入Endless之后，你会发现一个叫process.php的文件
7. 右键编辑打开文件（仅限电脑，不要使用手机，非常难受）
8. 如图找到第59-66行，具有https的三行是我们要更改的内容
   ![end](https://i.gyazo.com/d4f2918d414f31e00408c4dd1bc17798.png)
9. 改成我们在第四步的网址即可大功告成

### 域名+代理

目前搭建在我的服务商内，这里不会有任何权限问题，因为操作不适合新手。您也可以找一个CDN供应商以便于将控制权给您，请注意：转移后可能引起错误（操作错误），不进行操作也不会影响任何。

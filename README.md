# pxq_ticket

## 简介

基于 Tauri 开发的跨平台票星球客户端，可在 Linux、Windows 和 macOS 等操作系统上使用。

## 使用

- 手机应用商店下载票星球APP客户端或者微信小程序搜索票星球注册账号, 然后添加好观演人信息。
- 点击[下载](https://github.com/ClassmateLin/pxq_ticket/releases)二进制包, 安装即可。
- 使用短信验证码登录。
- 在演出页面搜索你需要购买的演唱会，然后点击按钮之后跳转到购买页面， 选择购票数量和观众，然后点击运行即可。


## 功能展示

## 短信登录

- 无图片验证码:

<img src="./imgs/sms_login_1.png" width = "640" height = "360" alt="无图形验证码登录" align=center />

- 有图片验证码:

<img src="./imgs/sms_login_2.png" width = "640" height = "360" alt="有图形验证码登录" align=center />

## 搜索演出

<img src="./imgs/show_search_1.png" width = "640" height = "360" alt="搜索" align=center />

<img src="./imgs/show_search_2.png" width = "640" height = "360" alt="搜索" align=center />

<img src="./imgs/show_search_3.png" width = "640" height = "360" alt="搜索" align=center />

<img src="./imgs/show_search_4.png" width = "640" height = "360" alt="搜索" align=center />


### 按钮说明

- 添加提醒: 官方确定会出售此演出的票, 但是未公布开售时间, 添加提醒之后, 当演唱会公布开售日期后会收到提醒短信。

<img src="./imgs/add_reminder.png" width = "640" height = "360" alt="搜索" align=center />

- 缺票登记: 前提条件演出门票已售完, 点击缺票登记, 在有票之后官方会发送短信通知。

<img src="./imgs/ticket_waitlist.png" width = "640" height = "360" alt="搜索" align=center />

- 立即购买: 已开售并且还有剩余票的情况下，可以直接购买。


<img src="./imgs/buy_now.png" width = "640" height = "360" alt="搜索" align=center />


- 加入抢票: 演出公布了售票日期后, 加入任务等待抢票。

<img src="./imgs/buy_now.png" width = "640" height = "360" alt="搜索" align=center />


## TODO

- 抢购逻辑写得比较匆忙, 勉强能用, 等待完善。
- 目前只有演出会类型可以下单成功, 其他类型的尚不支持。
- 订单列表
- 页面优化


## **[交朋友的点这里或扫码](https://faka577.site/buy/2)**

 <img src="./imgs/qr.png" width = "400" height = "400" alt="数量" align=center />


## 特别声明

- 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。
- 编写本项目主要目的为学习和研究Rust，无法保证项目内容的合法性、准确性、完整性和有效性。
- 本项目涉及的数据由使用的个人或组织自行填写，本项目不对数据内容负责，包括但不限于数据的真实性、准确性、合法性。使用本项目所造成的一切后果，与本项目的所有贡献者无关，由使用的个人或组织完全承担。
- 本项目中涉及的第三方硬件、软件等，与本项目没有任何直接或间接的关系。本项目仅对部署和使用过程进行客观描述，不代表支持使用任何第三方硬件、软件。使用任何第三方硬件、软件，所造成的一切后果由使用的个人或组织承担，与本项目无关。
- 本项目中所有内容只供学习和研究使用，不得将本项目中任何内容用于违反国家/地区/组织等的法律法规或相关规定的其他用途。
- 所有基于本项目源代码，进行的任何修改，为其他个人或组织的自发行为，与本项目没有任何直接或间接的关系，所造成的一切后果亦与本项目无关。
- 所有直接或间接使用本项目的个人和组织，应24小时内完成学习和研究，并及时删除本项目中的所有内容。如对本项目的功能有需求，应自行开发相关功能。
- 本项目保留随时对免责声明进行补充或更改的权利，直接或间接使用本项目内容的个人或组织，视为接受本项目的特别声明。

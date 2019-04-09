## **甜果果小铺商城案例（微信小程序）**


### *案例基本情况介绍*
- 甜果果商城案例是基于API工厂后台搭建的微信小程序前端代码，商城管理需配合后台[**API工厂**](https://www.it120.cc/login "API工厂")使用。API工厂账号免费注册使用，基本会员功能足以满足日常经营活动使用
- 本商城基于[EastWorld](https://github.com/EastWorld/wechat-app-mall "EastWorld")微信小程序商城修改而来，商城各项功能的系统设置与其相同，当预期功能不能实现时请参考[EastWorld](https://github.com/EastWorld/wechat-app-mall "EastWorld")使用说明\帮助文档进行设置修改。

### *商城预览*

##### **加载页：**
---
![加载页Alt](https://cdn.it120.cc/apifactory/2018/04/19/0643e587c46810617e2accfa7b1d408d.png "加载页")
#### **欢迎页：**
---
![授权Alt](https://cdn.it120.cc/apifactory/2018/04/19/b1471a03b047fe47347afa63dad405d9.png "授权页")
![欢迎页Alt](https://cdn.it120.cc/apifactory/2018/04/19/c0db49b1e7c15f18f8fbf7184d01404b.png "欢迎页")
#### **分类页：**
---
![分类页Alt](https://cdn.it120.cc/apifactory/2018/04/19/2ee6e067ea689dede5f9c37cfc3524d9.png "分类页")
![分类页Alt](https://cdn.it120.cc/apifactory/2018/04/19/561871b9a54f532eada6ff9a89a03731.png "分类页")
![分类页Alt](https://cdn.it120.cc/apifactory/2018/04/19/b983b2c22046f99851ea1bac14e1a89e.png "分类页")
#### **精选页：**
---
![精选页Alt](https://cdn.it120.cc/apifactory/2018/04/19/9bddf07c1923d209280b337bf86ab4c1.png "精选页")
#### **详情页：**
---
![详情页Alt](https://cdn.it120.cc/apifactory/2018/04/19/a23e1b8ca5d6fcabb65d02ee6b32f359.png "详情页")
#### **发现页：**
---
![发现页Alt](https://cdn.it120.cc/apifactory/2018/04/19/82674d9c98d2170d5d958b12100ed856.png "发现页")
![发现页Alt](https://cdn.it120.cc/apifactory/2018/04/19/3fddac77c1cdf86876e789d3d69c2179.png "发现页")
#### **搜索结果：**
---
![搜索结果Alt](https://cdn.it120.cc/apifactory/2018/04/19/a7a7a9587adc6c29e316294a8c412f50.png "搜索结果页")
#### **购物车：**
---
![购物车Alt](https://cdn.it120.cc/apifactory/2018/04/19/a806969f4a00ebec57cbc148ea0ace69.png "购物车页")
![购物车Alt](https://cdn.it120.cc/apifactory/2018/04/19/c459282a749ed4a299641edd612b1182.png "购物车页")
![购物车Alt](https://cdn.it120.cc/apifactory/2018/04/19/fc2f66958ce3de03c5113a4ebb1ab536.png "购物车页")
#### **提交订单：**
---
![提交订单Alt](https://cdn.it120.cc/apifactory/2018/04/19/b8741dffcc7259f23c6ffa698d05b0fa.png "提交订单页")
#### **订单列表：**
---
![订单列表Alt](https://cdn.it120.cc/apifactory/2018/04/19/9f1f636ed1f108409326a42dccba1ccc.png "订单列表页")
![订单列表Alt](https://cdn.it120.cc/apifactory/2018/04/19/7a699ebb3c03a34c8ca9bf5a2f009c74.png "订单列表页")
![订单列表滑动效果Alt](https://cdn.it120.cc/apifactory/2018/04/19/0a374f81b2fa26164a517c986bfc38d1.gif "订单列表页")
#### **订单详情：**
---
![订单详情Alt](https://cdn.it120.cc/apifactory/2018/04/19/256e1329bd0d71544f401fbef0fc1dfb.png "订单详情页")
#### **个人中心：**
---
![个人中心Alt](https://cdn.it120.cc/apifactory/2018/04/19/2d2adb6d4427bf9f67b3361ba7ea48d9.png "个人中心")
#### **钱包充值、提现：**
---
![钱包充值、提现Alt](https://cdn.it120.cc/apifactory/2018/04/19/c3b644f5b29044bac0845f2cdabf5d79.png "钱包充值、提现")
![钱包充值、提现Alt](https://cdn.it120.cc/apifactory/2018/04/19/40f304a9542ed6fb61ae01e8e4062166.png "钱包充值、提现")
#### **导航到店里：**
---
![导航到店里Alt](https://cdn.it120.cc/apifactory/2018/04/19/289f433247b5261575a6f8fdd9daf4e2.png "导航到店里")
#### **关于我们：**
---
![关于我们Alt](https://cdn.it120.cc/apifactory/2018/04/19/d8ea23a9cf8d57dc21375178fe47672b.png "关于我们")
---
### 使用配置说明：
- **微信公众平台基础配置**
	
    1. "设置"->"基本设置"->"基础库最低版本设置"为1.6.6(受所用组件库Minui限制，必须要在此版本只上才可以正常显示样式)
        
    2. "设置"->"开发设置"->"服务器域名"，此项需要配置，方法同[EastWorld](https://github.com/EastWorld/wechat-app-mall "EastWorld")(每一项都要设置为[https://api.it120.cc]\[https://cdn.it120.cc]),完成后检查微信官方开发者工具是否已经将此参数同步到本地。
>

- **API工厂平台基础配置**
    1. 此项配置请参见《基于East World数据库管理的甜果果小铺商城样例使用说明.pdf》说明。
    2. [EastWorld](https://github.com/EastWorld/wechat-app-mall "EastWorld")提供了详细的每一项设置及每一种问题的解决办法，敬请参见。

### 开放公共后台说明：

- 为方便大家调测试每一项功能，现开放一公有API账号公测。**账号下的任意内容请勿更改**，API工厂账号：11100000153，登陆password：2018。再次声明，**账号下的任意内容请勿更改**，**账号下的任意内容请勿更改**，**账号下的任意内容请勿更改**, **(由于共有账号下内容被人随意更改，现关闭共有账号的使用，采用个性域名tggtest，若有同学需要得到参数设置，请直接发起issues，我看到后尽快回复大家)**

- 账号下的微信支付模块请在“微信设置”中添加。

- **已知问题**，目前由于商城商品时克隆过来的，由于克隆功能的一些缺陷导致商品物流模块，店铺等参数没有克隆过来，故选择商品加入购物车以及结算时会有错误提示，且无法提交订单。包含了运费信息的账户则可以正常使用。















<meta http-equiv="refresh" content="0.5">

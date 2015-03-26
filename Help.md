### 1. 使用 ###
1.1 安装后，即可在地址栏内看到一个小地球图标

> 蓝色小地球表示正在使用代理访问该网站，点击可切换到“直接连接”访问

> ![http://buckyball.googlecode.com/hg/images/help2.jpg](http://buckyball.googlecode.com/hg/images/help2.jpg)

> 灰色小地球表示正在直接访问该网站，点击可切换到“使用代理”访问

> ![http://buckyball.googlecode.com/hg/images/help1.jpg](http://buckyball.googlecode.com/hg/images/help1.jpg)


### 2. 配置 ###

目前代理类型总共有五种：内置免费代理（GoAgent）、SSH代理、HTTPS代理、HTTP代理、系统代理

**2.1 内置免费代理（GoAgent）**

> 该代理类型为默认代理，基于goagent的原理，内置了一些账号供大家使用。

> ![http://buckyball.googlecode.com/hg/images/help3.jpg](http://buckyball.googlecode.com/hg/images/help3.jpg)

> 以后会考虑可以让使用自己的appid的。

**2.2 SSH代理**

> 配置混淆SSH代理前需要在SSH代理提供商处购买有SSH账号，[点此购买](ServiceProvider.md)

> ![http://buckyball.googlecode.com/hg/images/help4.jpg](http://buckyball.googlecode.com/hg/images/help4.jpg)

> 主机名：服务提供商指定的一个url或一个IP地址；

> 服务器端口：服务提供商制定的一个数字，0～65535间的一个数；

> 用户名和密码：在服务提供商处注册的账号密码，可咨询服务提供商；

> 本地端口号：自己填写，0到65535间任意一个不是正在用的端口号，建议使用默认。

> 混淆key：如果使用的是混淆SSH代理，服务商会指定一个字符串；如果使用的不是混淆的SSH代理，则此项不填。

**2.3 HTTPS代理**

> HTTPS代理有免费的（不好找且也不稳定），也有收费的（比如有些ssh提供商也提供有HTTPS代理的服务）。

> ![http://buckyball.googlecode.com/hg/images/help5.jpg](http://buckyball.googlecode.com/hg/images/help5.jpg)

> 不管是免费还是收费的，主机名和端口号都是由服务提供商提供的，可向其索取。

> 账号密码在连接时会提示输入登录。

**2.4 HTTP代理**

> 同HTTPS代理

> ![http://buckyball.googlecode.com/hg/images/help6.jpg](http://buckyball.googlecode.com/hg/images/help6.jpg)

**2.5 系统代理**

> 系统代理就是默认走系统IE的代理配置。

> ![http://buckyball.googlecode.com/hg/images/help7.jpg](http://buckyball.googlecode.com/hg/images/help7.jpg)
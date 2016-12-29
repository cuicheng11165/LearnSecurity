# 学习笔记 #


• 将一个鸡肋反射型XSS或是URL任意跳转漏洞转换为OAuth**

	• https://pan.baidu.com/s/1nv8oVBr

• 将一个非奖励范围内站点的影响扩散到范围内

	• 通过浏览器的跨域特性影响到其子站点

		○ document.domain 跨子域 DOM

		○ cookie 跨子域、跨协议

			§ 盗取上层域名 cookie

			§ 篡改或是覆盖cookie中的CSRF token，例如知乎

			§ 通过篡改或是覆盖cookie中值导致后门型XSS

		○ 

	• 同服务器则可以测试域名是否相同（如果需要厂商允许）

		○ CDN域名到子域：baiducdn.com => cdn.baidu.com

		○ static.zhihu.com = > www.zhihu.com/static


## 各个安全平台 ##

[http://0xsafe.org/](http://0xsafe.org/ "http://0xsafe.org/")

## 靶机训练 ##

dvwa

## 训练营  ##
[http://ctf.idf.cn/](http://ctf.idf.cn/ "http://ctf.idf.cn/")‘

## 公众号 TwoSecurity ##





• 学习常用的安全工具

	• AWVS

		a. 扫描靶场了解常见漏洞的攻击方式

		b. 通过漏洞报告学习漏洞原理

	• Burpsuite

		○ 学习 Proxy 抓包改包

		○ 学习 Intruder 爆破模块

		○ 学习实用  Bapp 应用商店中的插件

	• Nmap

		○ 使用 Nmap 探测目标主机所开放的端口

		○ 使用 Nmap 探测目标主机的网络服务，判断其服务名称及版本号

	• SQLMap

		○ 对 AWVS 中扫描出的 SQL 注入漏洞使用 SQLMap 进行数据获取

• 实践常见漏洞类型的挖掘与利用方式

	• 《黑客技术攻防宝典：Web实战篇》

		○ 有一定基础可以先看 9-12 章

• 练习常见 Web 漏洞的挖掘

	• http://www.vulnweb.com/

	• http://www.dvwa.co.uk/

		○ 使用 Docker 搭建https://hub.docker.com/r/citizenstig/dvwa/

• 关注安全资讯

	• http://freebuf.com/

	• http://bobao.360.cn/

	• http://wiki.ioin.in/

	• http://www.mottoin.com/






二进制安全：

《加密与解密》

《黑客之道漏洞发掘的艺术》

《黑客攻防技术宝典系统实战》



工控安全：

《工业控制系统信息安全》

《工业控制系统安全等级保护方案与应用》


漏洞挖掘：

《黑客技术攻防宝典：Web实战篇》

《白帽子讲Web安全》


○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061776.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061881.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061779.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061718.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061754.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061717.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2014-061668.html

○ http://wooyun.tangscan.cn/static/bugs/wooyun-2015-0141792.html


邮箱账户

		○ smtp @xxx.com

		○ smtp password

	• 后台地址

		○ admin password

	• 数据库信息

		○ Mysql root password

		○ sa password

	• 云服务的密钥

		○ aliyun_access_id

		○ ApiKey

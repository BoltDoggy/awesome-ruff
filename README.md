# Awesome Ruff [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://avatars2.githubusercontent.com/u/18478875?v=3&s=200" align="right" width="70">](https://ruff.io/zh-cn/)

软件定义硬件 https://ruff.io/zh-cn/

### 说明

通过[中文官网](https://ruff.io/zh-cn/)进行[购买](http://detail.koudaitong.com/show/goods?alias=35wmug7n0nrzf)、[下载](https://ruff.io/zh-cn/docs/download.html)，并阅读[入门文档](https://ruff.io/zh-cn/docs/)

这个仓库用来整理[社区](http://community.ruff.io/)内有价值的文章、[软件仓库](https://rap.ruff.io/)内更优秀的软件包，并收集网络更多相关资源，主要面向想尝试硬件编程的 JavaScript 开发者。

仓库内容等相关不提供其他交流平台，请直接提交 issue，另外 Ruff 相关技术问题，请移步专业社区。

Ruff 官方提供的 QQ 交流群：198194304。

## 目录

* [板子到手](#板子到手)
* [案例教程](#案例教程)
* [项目参考](#项目参考)
* [依赖推荐](#依赖推荐)
* [驱动开发](#驱动开发)
* [更多资源](#更多资源)

## 板子到手

* [固件升级](https://ruff.io/zh-cn/docs/firmware-upgrade.html) - 最新版会填平前人踩过的坑。
* [Ruff 救砖指南](http://community.ruff.io/t/ruff/303) - 啥，固件升级失败了，别慌。

## 案例教程

* [Lesson 1 - SOS 求救灯](http://community.ruff.io/t/ruff-lesson-1-sos/403)
* [Lesson 2 - 七彩循环灯](http://community.ruff.io/t/ruff-lesson-2/410)
* [Lesson 3 - LCD 抢答器](http://community.ruff.io/t/ruff-lesson-3-lcd/420)
* [Lesson 4 - LCD 温湿度计](http://community.ruff.io/t/ruff-lesson-4-lcd/451)

## 项目参考

* [~~ruffjs~~](https://github.com/ruffjs) - 官方仓库，暂未发现可供参考的项目案例，如需了解更多，请自行查阅。
  * [ruff-issues](https://github.com/ruffjs/ruff-issues/issues) - 对 ruff 有啥意见，来这里。
* [RuffApps](https://github.com/RuffApps) - 官方提供的项目参考
  * [ruff-tutorial](https://github.com/RuffApps/ruff-tutorial) - 案例教程中的完整项目。
  * [Apps](https://github.com/RuffApps/Apps) - 更多酷炫的项目参考。
  * more - 仓库内容不一一列举，请自行前往 github group 查阅。
* [ruff-drivers](https://github.com/ruff-drivers) - 官方驱动仓库

## 依赖推荐

* [ruff-menu](https://github.com/vilic/ruff-menu) - Awesome Menu for Ruff LCD (lcd1602).

## 驱动开发

* 驱动知识扩展 - 官方提供了维基百科地址，对于英文不好的同学，大概也就 ADC 稍微会在百度是时候懵逼吧。
  * [ADC](http://baike.baidu.com/subview/204037/8092697.htm#viewPageContent) - 模/数转换器
  * [gpio](http://baike.baidu.com/link?url=rdTNDO9sHHJKV2GFSOYmO0hxnNLlT7ZHVD76uU-CplBar6l8ER02ixb6_F0Wqz6X3jdnsUXlWOg6zJdFUETgSq) - 通用输入/输出，总线扩展器。
  * [I²C](http://baike.baidu.com/link?url=nQ4qTtTKtXeJ9Xe0xDnXMxGuKgbGPCIamWANIo6rueECCAOS31DDJoaJ2i7n-PNVqVuolSyUa-Zr2S0MDIpsgK) - 内部整合电路，是一种串行通讯总线，使用多主从架构，典型的电压准位为+3.3V(3v3)或+5v(5v0)。
  * [PWM](http://baike.baidu.com/link?url=p1rsOVGtv6fFufJlrNyrftrdLuUJggFW0qagCM1osj7LPh498aT9lhL_q4v4wPgUQym7KkHufkx-Epu9aLKoQrKy5IsNv6rAOEy2wO9KxqX_t4nwW5x3nivXLWNAnH0XhD-P4xeufS7fWdMwBbuOSK) - 脉冲宽度调制。
  * [UART](http://baike.baidu.com/link?url=TA4wQAJrCxf_cFoUxXd_XtDEPgIbLZJvCOXzC4jt-XYomOvp6YaVbSIwZ4ocMXpLoDGgl5jskuJGlOg10hjug_) - 通用异步收发传输器，是一种通用串行数据总线，用于异步通信。

## 更多资源

* [RuffHelper](https://github.com/runinspring/ruffhelper) - 一个 Ruff 开发辅助工具，把常用的 rap 命令可视化操作。
* [IoT and Ruff](https://codetimecn.com/episodes/iot) - 郑晔，分享他对物联网的理解。
* 友军
  * [Espruino](http://www.espruino.com/) - 它的 JavaScript 解释器给你实时的反馈, 在你敲入回车之后立即执行你输入的代码.
  * [Tessel](https://tessel.io/) - 支持 npm 的库，因此能够利用日益增长的 Node.js 的社区及其功能。
  * [JonnyFive](http://johnny-five.io/) - 直接用 Nodejs 开发 arduino 以及更多开发板。

**[⬆ 返回顶部](#目录)**

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
* [模块推荐](#模块推荐)
* [驱动开发](#驱动开发)
* [更多资源](#更多资源)

## 板子到手

* [~~Ruff Sparrow 说明书~~](https://ruff.io/zh-cn/sparrow/index.html) - 截止 2016.09.19，该页面外部设备驱动接口地址未更新。
* [固件升级](https://ruff.io/zh-cn/docs/firmware-upgrade.html) - 最新版会填平前人踩过的坑。
  * [1.5 升级说明](http://community.ruff.io/t/ruff-ap/460) - 默认使用 AP 模式
    * 绿灯亮表示开发板处于 AP 模式，就是说你电脑可以看到 Ruff_R0100932 这个热点
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

## 模块推荐

* [ruff-promise](https://github.com/vilic/ruff-promise) - Promise 实现
* [ruff-t](https://github.com/vilic/ruff-t) - BDD 风格的测试框架
* [ruff-home](https://github.com/vilic/ruff-home) - Web 开发框架
* [ruff-menu](https://github.com/vilic/ruff-menu) - 为 [LCD 1602](https://rap.ruff.io/devices/LCD1602-02) 提供的菜单程序库
* [ruff-fetch](https://github.com/vilic/ruff-fetch) - 一个简单的 HTTP 请求工具

## 驱动开发

* 驱动知识扩展
  * ADC - 模/数转换器
    * [Ruff](https://ruff.io/zh-cn/docs/adc.html) - [API](https://ruff.io/zh-cn/api/adc.html) | [Wiki](https://en.wikipedia.org/wiki/Analog-to-digital_converter) - [维基](https://zh.wikipedia.org/wiki/%E9%A1%9E%E6%AF%94%E6%95%B8%E4%BD%8D%E8%BD%89%E6%8F%9B%E5%99%A8) | [百度](http://baike.baidu.com/subview/204037/8092697.htm#viewPageContent)
  * gpio - 通用输入/输出，总线扩展器。
    * [Ruff](https://ruff.io/zh-cn/docs/gpio.html) - [API](https://ruff.io/zh-cn/api/gpio.html) | [Wiki](https://en.wikipedia.org/wiki/General-purpose_input/output) - [维基](https://zh.wikipedia.org/wiki/GPIO) | [百度](http://baike.baidu.com/link?url=rdTNDO9sHHJKV2GFSOYmO0hxnNLlT7ZHVD76uU-CplBar6l8ER02ixb6_F0Wqz6X3jdnsUXlWOg6zJdFUETgSq)
    * 驱动示例
      * [buzzer-gpio](https://rap.ruff.io/raps/buzzer-gpio) - [github](https://github.com/ruff-drivers/buzzer-gpio.git)
      * [button-gpio](https://rap.ruff.io/raps/button-gpio) - [github](https://github.com/ruff-drivers/button-gpio.git)
      * [sound-01](https://rap.ruff.io/raps/sound-01) - [github](https://github.com/ruff-drivers/sound-01.git)
      * [relay-1c](https://rap.ruff.io/raps/relay-1c) - [github](https://github.com/ruff-drivers/relay-1c.git)
      * [dht11](https://rap.ruff.io/raps/dht11) - [github](https://github.com/ruff-drivers/dht11.git)
      * [ruff-v1-infrared-sender](https://rap.ruff.io/raps/ruff-v1-infrared-sender) - [github](https://github.com/ruff-drivers/ruff-v1-infrared-sender.git)
      * [ruff-v1-infrared-receiver](https://rap.ruff.io/raps/ruff-v1-infrared-receiver) - [github](https://github.com/ruff-drivers/ruff-v1-infrared-receiver.git)
      * [flame-gpio](https://rap.ruff.io/raps/flame-gpio)
      * [sw-1801p](https://rap.ruff.io/raps/sw-1801p)
      * [hc-sr501](https://rap.ruff.io/raps/hc-sr501) - [github](https://github.com/ruff-drivers/hc-sr501.git)
  * I²C - 内部整合电路，是一种串行通讯总线，使用多主从架构，典型的电压准位为+3.3V(3v3)或+5v(5v0)。
    * [Ruff](https://ruff.io/zh-cn/docs/i2c.html) - [API](https://ruff.io/zh-cn/api/i2c.html) | [Wiki](https://en.wikipedia.org/wiki/I%C2%B2C) - [维基](https://zh.wikipedia.org/wiki/I%C2%B2C) | [百度](http://baike.baidu.com/link?url=nQ4qTtTKtXeJ9Xe0xDnXMxGuKgbGPCIamWANIo6rueECCAOS31DDJoaJ2i7n-PNVqVuolSyUa-Zr2S0MDIpsgK)
    * 驱动示例
      * [lcd1602-pcf8574a-hd44780](https://rap.ruff.io/raps/lcd1602-pcf8574a-hd44780) - [github](https://github.com/ruff-drivers/lcd1602-pcf8574a-hd44780)
      * [gy-30](https://rap.ruff.io/raps/gy-30) - [github](https://github.com/ruff-drivers/gy-30.git)
  * PWM - 脉冲宽度调制。
    * [Ruff](https://ruff.io/zh-cn/docs/pwm.html) - [API](https://ruff.io/zh-cn/api/pwm.html) | [Wiki](https://en.wikipedia.org/wiki/Pulse-width_modulation) - [维基](https://zh.wikipedia.org/wiki/%E8%84%88%E8%A1%9D%E5%AF%AC%E5%BA%A6%E8%AA%BF%E8%AE%8A) | [百度](http://baike.baidu.com/link?url=p1rsOVGtv6fFufJlrNyrftrdLuUJggFW0qagCM1osj7LPh498aT9lhL_q4v4wPgUQym7KkHufkx-Epu9aLKoQrKy5IsNv6rAOEy2wO9KxqX_t4nwW5x3nivXLWNAnH0XhD-P4xeufS7fWdMwBbuOSK)
    * 驱动示例
      * [ky-016](https://rap.ruff.io/raps/ky-016) - [github](https://github.com/ruff-drivers/ky-016.git)
  * UART - 通用异步收发传输器，是一种通用串行数据总线，用于异步通信。
    * [Ruff](https://ruff.io/zh-cn/docs/uart.html) - [API](https://ruff.io/zh-cn/api/uart.html) | [Wiki](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver/transmitter) - [维基](https://zh.wikipedia.org/wiki/UART) | [百度](http://baike.baidu.com/link?url=TA4wQAJrCxf_cFoUxXd_XtDEPgIbLZJvCOXzC4jt-XYomOvp6YaVbSIwZ4ocMXpLoDGgl5jskuJGlOg10hjug_)

## 更多资源

* [Ruff 和 nodejs 在 API 上有何区别](./Ruff-vs-Nodejs-of-API.md)
* [RuffHelper](https://github.com/runinspring/ruffhelper) - 一个 Ruff 开发辅助工具，把常用的 rap 命令可视化操作。
* [IoT and Ruff](https://codetimecn.com/episodes/iot) - 郑晔，分享他对物联网的理解。
* [Ruff 和树莓派的区别是什么？](https://www.zhihu.com/question/46707793) - 简而言之，Ruff 是一套软件，树莓派是一个硬件。
* 友军
  * [Espruino](http://www.espruino.com/) - 它的 JavaScript 解释器给你实时的反馈, 在你敲入回车之后立即执行你输入的代码.
  * [Tessel](https://tessel.io/) - 支持 npm 的库，因此能够利用日益增长的 Node.js 的社区及其功能。
  * [JonnyFive](http://johnny-five.io/) - 直接用 Nodejs 开发 arduino 以及更多开发板。
  * [Duktape](http://www.duktape.org/) - 一个新的小巧的超精简可嵌入式 JavaScript 引擎。
  * [cylonjs](https://cylonjs.com/) - 一个为机器人学和物联网服务的开发的 Javascript 框架。
  * [iotjs](www.iotjs.net) - 一个使用 JavaScript 语言编写的物联网应用平台
    * [jerryscript](https://github.com/Samsung/jerryscript) - 一个轻量级的 JavaScript 引擎，它可以运行在受限制的设备上，例如微控制器

**[⬆ 返回顶部](#目录)**

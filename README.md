<!--
 * @Author: moonmist.guan
 * @Date: 2020-03-06 20:36:00
 * @LastEditTime: 2020-03-07 19:51:07
 * @FilePath: /undefined/Users/moonmist/OneDrive/Code/6700k_z170_rx580_Hackintosh/README.md
 * @Description: 
 -->

# 6700k+z170a+rx580黑苹果EFI

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

因为开发需要使用Mac，所以在原先的组装机上装了黑苹果，经过一段时间测试，各项功能基本良好，适配于macOS Catalina 10.15.3，本方案是在大量前人经验基础上总结得到到，感谢他们的辛勤付出


## Table of Contents

- [Background](#background)
- [Install](#install)
- [Maintainers](#maintainers)
- [License](#license)

## Background

作为一名程序员，有记笔记的习惯但是很惭愧一直没有自己的博客，正好借此机会开发一套适合自己需求的blog框架



## Install

下载之后使用Clover Confifguration挂载启动分区，使用本EFI替换即可，替换之前请注意保存原有EFI，谨防不测




## 更新记录

>2020.03.07
>
>* 修复核显及显卡硬解码
>* 修改机型为Imac Pro(2017)提高系统适配稳定
>* 美化Clove启动去除启动代码








![](http://ww2.sinaimg.cn/large/006tNc79gy1g5w0vrvzw2j319g0u0dlr.jpg)





黑苹果镜像下载地址:https://blog.daliansky.net/macOS-Catalina-10.15.3-19D76-Release-version-with-Clover-5103-original-image-Double-EFI-Version.html

镜像[下载](https://blog.daliansky.net/macOS-Catalina-10.15.3-19D76-Release-version-with-Clover-5103-original-image-Double-EFI-Version.html)




## 设备大概配置情况

|  类别  |   型号    |  状态  | 其他                                                         |
| :----: | :-------: | :----: | :----------------------------------------------------------- |
| 处理器 | i7-6700k |  正常  |       变频正常，平衡性能与功耗                                                       |
|  屏幕  |    2台显示器     |  正常  | 1台27 1080P，1台34 1080p，显示正常，可以一键开启HDIP                                                 |
|  显卡  |   RX580   |  正常  | 使用的是RX580 8G 2304sp满血版，显卡功能正常，日常功耗60w|
|  睡眠  |           |  正常  | 睡眠正常，可正常唤醒，偶发关机重启 |
|  USB   |           |  正常  | 所有usb接口和速度正常                                   |
|	雷电3  ||待验|理论正常，但是手头没有设备测试|
| 以太网卡 ||正常|正常|
| WiFi |暂无| |P51的黑苹果使用原生网卡，随航等功能都OK，台式机暂时没有加入无线网卡和蓝牙|
| 快捷键 ||正常|一切正常|
| 显示器亮度 ||基本正常|需要通过软件进行调节亮度|
| 音频 ||基本正常|板载接口正常，通过HDMI外接显示器时显示器音量需要通过软件条件，基本能正常|
| 待补充 ||||












## Maintainers

[@Guanzj](https://github.com/Guanzj).


## License

[MIT](LICENSE) © Monnmist

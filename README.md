# Bilibili-Helper-Chrome-Extension

Bilibili-Helper 是一款能够为 B站用户 提供 视频弹幕热度的 Chrome 插件。

<p align="center">
  <a href="https://media.giphy.com/media/f9XpASOHKdr1aaM2zx/giphy.gif">
    <img src="https://media.giphy.com/media/f9XpASOHKdr1aaM2zx/giphy.gif">
  </a>
</p>

## Introduction & Inspiration

Bilibili-Helper 是一款 致力于为 B 站用户提供人性化逛站工具的 Chrome 插件。

其提供的主要功能为：**弹幕/视频 热点的准确定位**

本人喜欢在 B 站上看英雄联盟比赛的录播，苦于录播时间长，往往需要手动拉进度条，找开团的时间点，于是我干脆自己做了一个插件，通过弹幕热度，帮助自己找到视频热点。效果如图：

![image-20201109110356251](assets/image-20201109110356251.png)


该插件能够在视频加载完成后，在视频下方生成一个弹幕热度图，通过弹幕热度，我们可以比较准确的定位视频的热点，上图的比赛中，开局后的每一个弹幕峰值，往往都是一次团战或者击杀。

## Download & Installation

* [Github Release](https://github.com/wansho/bilibili-helper-chrome-extension/releases)
* [Chrome Extension](https://chrome.google.com/webstore/detail/bilibili-helper/hdppmpnmokdiaabkhgnooeimhmbahdkm?hl=zh-CN&gl=CN)
* [百度网盘](https://pan.baidu.com/s/14uFFnoBGUITDbLWjDOqc-A)  提取码: 3sgg

关于如何离线安装 Chrome 插件，请手动百度关键词：*Chrome 插件离线安装*

## Tutorial

<img align="left" src="assets/image-20201109110415727.png" alt="image-20201109110415727" style="zoom: 67%;" />


打开 弹幕热度开关 即可放心食用弹幕热度插件。

## Dev

### Data Flow

![data-flow](http://assets.processon.com/chart_image/5cad413ae4b0b39803e4165b.png?_=1554860808775)

## Todo

目前该插件主要功能已实现，但仍有很多 Bug，后期有时间的话，我会把以下问题都解决：

* 实现番剧的弹幕分析兼容
* 实现全屏时的兼容 —> 完成
* 高能定位 —> 完成
* 完善用户UI —> 完成（使用了 material design 的 UI）

如果你在使用中发现重大的Bug，欢迎来 Github 提交 issue 进行反馈。


---
title: 简洁的 Mac 图床客户端 uPic
date: 2019-06-24 20:42:43
thumbnail: //s2.svend.cc/thumb/done.svg
toc: true
widgets:
  - type: toc
    position: right
sidebar:
  left:
    sticky: true
  right:
    sticky: true
---

<div align="center">
  <img src="https://gitee.com/gee1k/uPic/raw/master/screenshot/logo.png" alt="uPic">
</div>

# ☁️ 简洁的 Mac 图床客户端 uPic

<div style="display: flex;justify-content: center;">
   <a href="https://github.com/gee1k/uPic/stargazers">
    <img src="https://img.shields.io/github/stars/gee1k/uPic.svg?style=popout-square" alt="">
  </a> <a href="https://github.com/gee1k/uPic/releases" style="margin: 0 5px;">
    <img src="https://img.shields.io/github/downloads/gee1k/uPic/total.svg?style=popout-square" alt="">
  </a> <a href="https://github.com/gee1k/uPic/releases/latest">
    <img src="https://img.shields.io/github/release/gee1k/uPic.svg?style=popout-square" alt="">
  </a>
</div>

## 📑 简介

> **uPic 是一款 Mac 端的图床(文件)上传客户端**
> 可将图片、各种文件上传到配置好的指定提供商的对象存储中。
> 然后快速获取可供互联网访问的文件 URL

## 💡 特点

无论是本地文件、或者屏幕截图都可自动上传，菜单栏显示实时上传进度。上传完成后文件链接自动复制到剪切板，让你无论是在写博客、灌水聊天都能快速插入图片。
连接格式可以是普通 URL、HTML 或者 Markdown，仍由你掌控。

## 📤 上传方式

为了满足你可能遇到的各种需求，uPic 提供了多种上传方式

- ✅ 选择文件上传
- ✅ 复制文件上传
- ✅ 拖拽文件上传
- ✅ 截图上传

#### 🖥 选择文件上传

![选择文件上传](https://gitee.com/gee1k/uPic/raw/master/screenshot/selectFile.gif)

#### ⌨️ 复制文件上传

![复制文件上传](https://gitee.com/gee1k/uPic/raw/master/screenshot/paste.gif)

#### 🖱 拖拽文件上传

![拖拽文件上传](https://gitee.com/gee1k/uPic/raw/master/screenshot/drag.gif)

#### 🖱 截图上传

![截图上传](https://gitee.com/gee1k/uPic/raw/master/screenshot/screenshot.gif)

## 📦 图床、对象存储

- [smms](https://sm.ms/)
- [又拍云 USS](https://www.upyun.com/products/file-storage)
- [七牛云 KODO](https://www.qiniu.com/products/kodo)
- [阿里云 OSS](https://www.aliyun.com/product/oss/)
- [腾讯云 COS](https://cloud.tencent.com/product/cos)
- [微博](https://weibo.com/)
- [Github](https://github.com/settings/tokens)
- [Gitee](https://gitee.com/profile/personal_access_tokens)
- [自定义上传接口](https://blog.svend.cc/upic/tutorials/custom)
- ...

#### ⚙️ 配置图床

**在`偏好设置`中可配置图床。支持同一类型图床可配置多个实例**

![图床配置](https://gitee.com/gee1k/uPic/raw/master/screenshot/hosts.png)

#### 🔦 选择图床

**配置好的图床可以在菜单栏`图床`中看到，并选择您接下来要上传到的图床**

![图床](https://gitee.com/gee1k/uPic/raw/master/screenshot/default-host.png)

## 🧰 更多功能

**除了以上这些最基本的功能以外，uPic 还提供了一系列小功能让你使用起来更方便更顺心**

### ⌨︎ 全局快捷键

![快捷键](https://gitee.com/gee1k/uPic/raw/master/screenshot/shortcuts.png)

### 🕦 上传历史

![上传历史](https://gitee.com/gee1k/uPic/raw/master/screenshot/history.png)

### 📢 更多功能等待你发现

...

# 💌 联系我

- `Email`: svend.jin@gmail.com
- `微信`: `JSW5297` (请备注一下 uPic)
- `Telegram`: [gee1k](https://t.me/gee1k)
- `项目地址`: [Github](https://github.com/gee1k/uPic)
- `uPic 产品交流群(微信)`:
  <img src="https://raw.githubusercontent.com/gee1k/oss/master/personal/uPic-wechat.JPG" alt="uPic产品交流群" style="width: 300px;" align="center">

# 📝 使用手册

- [uPic 图床配置教程 - 微博](./tutorials/weibo)
- [uPic 图床配置教程 - 又拍云](./tutorials/upyun_uss)
- [uPic 图床配置教程 - 七牛云](./tutorials/qiniu_kodo)
- [uPic 图床配置教程 - 阿里云](./tutorials/aliyun_oss)
- [uPic 图床配置教程 - 腾讯云](./tutorials/tencent_cos)
- [uPic 图床配置教程 - Github](./tutorials/github)
- [uPic 图床配置教程 - 码云(Gitee)](./tutorials/gitee)
- [uPic 图床配置教程 - 自定义上传](./tutorials/custom)
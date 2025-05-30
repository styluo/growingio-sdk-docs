---
title: 版本记录
sidebar_position: 0
---

## [1.2.0](https://github.com/growingio/growingio-sdk-harmonyos/tree/giokit-1.2.0) (2025-04-08)

### Features 功能

* feat: 支持 UseInRelease
* feat: 增加显示是否延迟初始化，是否正确集成无埋点
* chore: buildOption.arkOptions.byteCodeHar 改为 false，不再作为字节码 har 发布

### Bug Fixes 修复

* fix: 修复 GioKit Window 占用焦点导致 router 跳转等功能异常

## [1.1.0](https://github.com/growingio/growingio-sdk-harmonyos/tree/giokit-1.1.0) (2024-11-14)

### Features

* feat: 兼容 SDK 2.1.0(支持 protobuf 数据格式传输)

## [1.0.1](https://github.com/growingio/growingio-sdk-harmonyos/tree/giokit-1.0.1) (2024-10-25)

### Bug Fixes

* fix: 替换已废弃的接口 util.TextDecoder().decodeWithStream

## [1.0.0](https://github.com/growingio/growingio-sdk-harmonyos/tree/giokit-1.0.0) (2024-09-10)

* SDK 信息 - 全面的 SDK 集成信息与 App 基本信息，方便截图分享
* 事件库 - 实时埋点数据浏览，包括数据发送状态，发送数据详情
* 网络记录 - 埋点事件请求抓包工具，实时查看埋点数据上传进度
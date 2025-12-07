## 关于这个仓库

本仓库用于发布 less-process（兼程） 的 Release 版本以及使用 Github Issues 收集和跟进用户反馈。

兼程 **并非开源软件**，这个仓库并 **不包含** less-process 的源代码。

我们要做一个能让所有的人，都能受益的应用。

### 应用介绍

本地优先的笔记以及效率工具集合
新一代效率工具聚合

less-process 是一款离线运行，提供 markdown，todo 等多种内容格式支持的应用

## 使用的技术栈

> [查看更详细的技术栈](./docs/design/参考资料.md)

- tauri（打包应用，提供本地文件操作 API）
- vite（前端开发、打包工具）
- React（最受欢迎的前端框架，提供了强大的社区，有很多现成的轮子）
- shadcn（直接安装到项目中的 UI 库，可控性更高）
- shiki（代码美化工具，支持多种编程语言，多种主题）
- milkdown（提供所见即所得的 markdown 编辑体验）

## 项目版本

每两周一个补丁版本，1~2 个月一个副版本，1 ~ 2 年一个主版本

## 系统支持

这些系统保证绝对可用

- windows 10 及以上
- linux
  - ubuntu 20.04 以上
  - debian 12 以上
- Mac 暂时没有电脑，不保证绝对可用
- android 8 以上
- ios 14 以上

在 Windows 10（2018 年 4 月发布或之后的版本）和 Windows 11 上，WebView2 运行时作为操作系统的一部分进行分发。因为 tauri 依赖于 webview，所以必须更新 windows 到版本

应用当前使用的是 tailwindcss v4，需要以下版本及以上的浏览器

- Safari 16.4 (released March 2023)
- Chrome 111 (released March 2023)
- Firefox 128 (released July 2024)

> Chrome 109 is the last version of Chrome that will support Windows 7, Windows 8/8.1
> 因此不支持 win7
> 应用面向浏览器
> Browserslist，支持的浏览器
> targets: [ 'chrome >0 and last 2.5 years', 'edge >0 and last 2.5 years', 'safari >0 and last 2.5 years', 'firefox >0 and last 2.5 years', 'and_chr >0 and last 2.5 years', 'and_ff >0 and last 2.5 years', 'ios >0 and last 2.5 years', ]

## 支持开发者

3元，让开发者快乐一下
30元，让开发者痛苦的肝新功能

## 项目集合

- less-process 应用本体
- less-process-page 应用官网
- less-process-doc 应用的使用方式以及应用的技术栈介绍
- less-process-backend 应用后端
- less-process-manage 应用管理端

## 待办内容

- ROADMAP 宏观上需要实现的内容
- TODO 所有待办的内容
- TIMELINE 按照时间顺序梳理需要做的内容
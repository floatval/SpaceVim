---
title: "SpaceVim lang#lisp 模块"
description: "这一模块为 lisp 开发提供支持，包括代码补全、语法检查、代码格式化等特性。"
---

# [可用模块](../../) >> lang#lisp

<!-- vim-markdown-toc GFM -->

- [模块简介](#模块简介)
- [启用模块](#启用模块)
- [环境依赖](#环境依赖)
- [快捷键](#快捷键)

<!-- vim-markdown-toc -->

## 模块简介

这一模块为 SpaceVim 提供了 lisp 开发支持，包括代码补全、语法检查、以及代码格式化等特性。

## 启用模块

可通过在配置文件内加入如下配置来启用该模块：

```toml
[[layers]]
  name = "lang#lisp"
```

## 环境依赖

- Vim 8.0+ 且编译了 +channel, 或则 Neovim0,2.0+ 编译了ncat
- ASDF
- Quicklisp
- 一个用来从 Quicklisp 中安装其他依赖的正常网络连接

## 快捷键

所有语言的特定快捷键都是以 `[SPC]` 开始的,详情请参阅按键引导.

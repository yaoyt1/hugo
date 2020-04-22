+++
title="20200302 Typescript 配置环境和工具"
tags=["typescript基础","环境配置"]
categories=["typescript"]
date=2020-03-02T08:34:38+08:00
toc=true
+++

# TypeScript 环境

## 安装node.js
  > * [node.js下载](https://nodejs.org/en/download/)
## 安装TypeScript
  > * cmd 命令运行node.js命令安装TS: npm install -g typescript
## 高版本的游览器有些是支持TS
  > * 高版本的可以直接导入TS引用
## 编译成js
  > * tsc hellword.ts
## 编译器自动编译
  > * vscode 自动编译
  > * 项目目录下运行 tsc --init 
  > * 修改tsconfig.json的目标输出文件夹
  > * 然后点击终端=>运行任务=>tsc 监视-typescript 如图![如图](../images/post/typescript/demo1.jpg)

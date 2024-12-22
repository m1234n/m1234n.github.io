---
title: windows常用命令
date: '2024-12-22 13:49:04'
updated: '2024-12-22 18:13:52'
tags:
  - windows
  - 命令行
permalink: /post/windows-commonly-used-commands-2vsuxn.html
comments: true
toc: true
---



# windows常用命令

* 更换winget源

  ```powershell
  #替换源USTC源
  winget source remove winget
  winget source add winget https://mirrors.ustc.edu.cn/winget-source

  //重置为官方地址
  winget source reset winget
  ```

‍

* 更换npm镜像源

  ```powershell
  # 淘宝镜像源
  npm config set registry https://registry.npmmirror.com
  npm config get registry

  #恢复官方源
  npm config set registry https://registry.npmjs.org
  ```

‍

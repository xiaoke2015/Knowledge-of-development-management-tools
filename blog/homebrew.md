# Homebrew
The Missing Package Manager for macOS (or Linux)

## 解决问题

Homebrew是一款软件包管理工具，拥有安装、卸载、更新、查看、搜索等很多实用的功能。简单的一条指令，就可以实现包管理，而不用你关心各种依赖和文件路径的情况，十分方便快捷。

## 技术支持

* [Homebrew](https://brew.sh)

## 相关操作

1. 安装 Homebrew

    vpn 正常安装

    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

    国内安装

    `/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"`

 
2. 使用

    安装软件

    `brew install cocoapods`

    查询安装软件

    `brew list`

    卸载软件

    `brew uninstall cocoapods`

3. 安装路径

    Homebrew 路径

    `/usr/local/Homebrew`

    Homebrew 软件包路径

    `/usr/local/Cellar`


## 问题记录

1. 安装Homebrew 时，没反应一直卡在Downloading Command Line Tools for Xcode

    解决: 前往Apple开发者网站，下载符合上方提示使用中Xcode版本的Command Line Tools


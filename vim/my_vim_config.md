---
title: 一份适合C/C++/markdown/html/css/js的vim配置
date: 2017-10-30 21:35:25
categories:
    - vim
tags:
    - vim
    - vim config
abbrlink: 00e87c3d0f40340b
---

这是我的vim配置：[my vim config](https://github.com/qw8880000/vim_config).
linux 下的vim 与 windows 下的gvim 通用。

# 截图

![screenshot for molokai](http://oxnimkw03.bkt.clouddn.com/20171030101917.png)

主题：molokai

# vim 配置文件 

此vimrc适合如下开发：

-   c/c++ 
-   html/css/js

# 安装 

注意，所有的操作之前需要先安装`git`

## 对于linux

1. `git clone https://github.com/qw8880000/vim_config.git ~/vim_config`
1. 创建符号链接 `ln -s ~/vim_config/_vimrc ~/.vimrc`
1. 创建目录 `mkdir ~/.vim`
1. 安装Vundle `git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle`
1. 打开vim，输入 `:BundleInstall` 来安装其他插件 

然后安装 ctags 和 cscope

1. `sudo apt-get install ctags`
1. `sudo apt-get install cscope`

## 对于windows (gvim)

1. 下载gvim并安装
1. 复制我的配置文件`_vimrc`与`_gvimrc` 到正确的位置，如下图
![image](http://oxnimkw03.bkt.clouddn.com/20171030221516.png)
1. 在vimfiles 文件夹下新建文件夹 bundle
1. 切换目录到`vimfiles/bundle`，执行安装Vundle的命令 `git clone https://github.com/gmarik/vundle.git`
1. 打开vim，输入 `:BundleInstall` 来安装其他插件 

# 插件列表

| plugin                        |
|-------------------------------|
| gmarik/vundle                 |
| junegunn/vim-easy-align       |
| Shougo/neocomplcache.vim      |
| OmniCppComplete               |
| Shougo/neosnippet.vim         |
| Shougo/context_filetype.vim   |
| qw8880000/neosnippet-snippets |
| bufexplorer.zip               |
| scrooloose/nerdtree           |
| majutsushi/tagbar             |
| qw8880000/ccvext.vim          |
| ctrlpvim/ctrlp.vim            |
| Lokaltog/vim-powerline        |
| scrooloose/syntastic          |
| easymotion/vim-easymotion     |
| terryma/vim-multiple-cursors  |
| tomasr/molokai                |
| tpope/vim-fugitive            |
| mattn/emmet-vim               |
| pangloss/vim-javascript       |
| maksimr/vim-jsbeautify        |
| leshill/vim-json              |
| heavenshell/vim-jsdoc         |
| gko/vim-coloresque            |
| qw8880000/DoxygenToolkit.vim  |
| justinmk/vim-syntax-extra     |
| qw8880000/c.vim               |
| cpp.vim                       |
| scrooloose/nerdcommenter      |
| TxtBrowser                    |
| plasticboy/vim-markdown       |
| qw8880000/vim-tab             |

# 快捷键

* 显示目录树 `F2`
![image](http://oxnimkw03.bkt.clouddn.com/f2.gif)

* 显示本文件的代码结构 `F4`
![image](http://oxnimkw03.bkt.clouddn.com/f4.gif)

* 在打开过的文件之间切换 `,be`
![image](http://oxnimkw03.bkt.clouddn.com/bufexplore.gif)

* 切换到右边的窗口 `ctrl + l`, 切换到左边的窗口 `ctrl + h`
![image](http://oxnimkw03.bkt.clouddn.com/winChange.gif)

* 在目录树中定位当前文件 `,nf`
![image](http://oxnimkw03.bkt.clouddn.com/findCurrentFile.gif)

* 生成 doxygen author 注释 `,da`
![image](http://oxnimkw03.bkt.clouddn.com/DoxAuthor.gif)

* 生成doxygen函数注释 `,dx`
![image](http://oxnimkw03.bkt.clouddn.com/DoxFunction.gif)

* 生成注释(每行都生成注释) `,ci`. 取消注释 `,cu`.
![image](http://oxnimkw03.bkt.clouddn.com/comment1.gif)

* 生成注释(整块注释) `,cm`. 取消注释 `,cu`.
![image](http://oxnimkw03.bkt.clouddn.com/comment2.gif)

* 在行尾生成注释 `,cA`
![image](http://oxnimkw03.bkt.clouddn.com/comment3.gif)

* 在 `/**/` 与 `//` 之间切换 `,ca`
![image](http://oxnimkw03.bkt.clouddn.com/comment4.gif)

# 其他

* [其他配置参考](https://github.com/VundleVim/Vundle.vim/wiki/Examples)


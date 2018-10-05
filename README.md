# mac-
mac node.js 开发装机


### Mac使用终端安装Homebrew(brew)
https://blog.csdn.net/boyqicheng/article/details/71481213?utm_source=itdadao&utm_medium=referral

### 安装Mysql
```
brew install mysql  
```

### Navicat Premium Mac 12 
1. https://www.jianshu.com/p/f42785e55b6b
2. https://blog.csdn.net/xhd731568849/article/details/79751188

### 安装Git 
在命令行输入 git -v 就会自动提示引导安装

### 安装 [n](https://github.com/tj/n) 管理node.js 的版本
```
curl -L https://git.io/n-install | bash

. ~/.bashrc
```
使用n来安装最新的node.js
```
n latest
node -v
//检查安装后的node 的版本
npm -v 
//检查安装后的npm 的版本
```

### 安装 [redies](https://redis.io) 管理缓存
https://www.jianshu.com/p/2123bfbb1139

### 安装 [GraphicsMagick](http://www.graphicsmagick.org/INSTALL-unix.html) 用来做图片处理
```
brew install graphicsmagick
gm -version
```

### 安装 [ImageMagick](https://www.imagemagick.org) 用来做图片处理
```
brew install ImageMagick
```

### 安装[VS Code](https://code.visualstudio.com) IDE
自行到官网下载安装

配置 vsc 命令在控制台快速打开项目
1、打开用户配置文件：
```
vim ~/.bash_profile
```
2、添加别名
```
#配置Visual Studio Code的命令行方式
alias vsc="'/Applications/Visual Studio Code.app/Contents/Resources/app/bin/code'"
```
如果不添加别名，也可以将路径添加到环境变量下
```
VSC_BIN=/Applications/Visual Studio Code.app/Contents/Resources/app/bin
PATH=$VSC_BIN:$PATH
export PATH
```
3、保存后回到命令行终端执行命令使其生效：
```
source ~/.bash_profile
```

#### VScode 插件工具集
https://blog.csdn.net/qq_41164267/article/details/82767554

#### Eslint 和 VScode的相关配置
https://segmentfault.com/a/1190000009077086?from=timeline&isappinstalled=0



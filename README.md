# git

1、安装下载git。
    （1）Linux 安装方法：sudo apt-get install git
    （2）Mac OS X安装方法：
        I、下载homebrew，后通过homebre下载。
        II、下载Apple开发工具Xcode，集成git。通过终端输入git，根据提示更新，下载开发者命令行工具。
     (3)Windows安装方法：下载exe文件。

2、全局配置（仓库用户名及邮件地址）：
     git config --global user.name “yourname”
     git config --global user.email "youremail address"
     执行完成后，将在~目录下生成一个隐藏文件.gitconfig,
     [user]
         name = yourname
         email = youremail address

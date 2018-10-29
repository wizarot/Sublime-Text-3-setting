# 我的 Sublime Text3配置和安装包备份

## 说明

暂时这个项目作用就是节省下每次安装配置软件的问题了.可能有其它更简单方式,有空再研究.

## 找到Sublime Text 3的配置安装位置
1. 首先安装软件
2. 通常情况下在这个位置
```
cd ~/Library/Application\ Support/Sublime\ Text\ 3
```
3. 如果没有,那么就按照这个方法找找试试: [找到备份目录](https://www.jianshu.com/p/2c70c0100711)


##  恢复方式

删除Installed Packages,Packages文件夹，把远程仓库中的插件pull下来

```
rm -Rf Installed\ Packages
rm -Rf Packages
git init
git remote add origin https://github.com/wizarot/Sublime-Text-3-setting.git
git pull origin master
```
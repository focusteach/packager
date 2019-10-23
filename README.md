# packager
packager cross platform 
一个可在线打包的打包工具

## 打包工具
* 将安装文件作为go 内置资源
* 可以编辑的用户脚本
* 版本管理
* 文件压缩
* 打包安装器
* 打包卸载器

## go安装器
实现以下功能
* 打开时释放UI程序（预先编译好的），并启动
* 与UI进行交互
* 文件释放到安装目录下
* 执行用户指定命令
* 释放卸载器到安装目录
* 下载安装升级器（可选）

## 卸载器
* 卸载器UI（预先编译好的），可自定义UI
* 卸载器执行用户脚本
* 自删除

## 升级器
* 升级器UI，不可自定义UI，通用

## UI程序
* 分安装器和卸载器的
* 用户UI可定制（xml方式）

# CHANGELOG

## To do

1. 可视化管理工具
2. AmazonLinux支持
3. 配置文件覆盖问题(httpd.conf, php.ini. vhost.conf)
4. 部分应用无需创建数据库，该项目的变量文件中如何定义？
5. 检查非git下载的安装包解压后的目录名称

## Logs

### Bug Fixes

* 2020-09-21  php_ioncube: "{{ (phpapps_name == 'chanzhi' or phpapps_name == 'zdoo') | ternary(True,False) }}" replace include var
* 2020-06-23  VtigerCRM制作镜像后初始化页面报错的问题

### Features

* 2020-09-23  Dzzoffice integrated onlyofficedocumentserver
* 2020-08-15  Change to phpMyAdmin on Docker
* 2020-02-20  new init password solution
* 2020-02-17  created, support multi-os, multi-webserver

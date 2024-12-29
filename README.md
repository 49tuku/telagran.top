纸飞机中文版源码是采用PHP开发的一款电脑版Web管理系统。FastAdmin是一款基于ThinkPHP+Bootstrap的极速后台开发框架。喜欢的朋友可以研究学，如果下载Telegram中文版代码文件很慢，可以通过百度网盘下载，然后使用vagrant box add dongweiming/web_develop virtualbox.box初始化；地址：[Telegram中文版下载](https://www.telagran.top/)

## 如果使用Telegram中文版启动时，提示类似如下信息：
```
==> default: A newer version of the box 'dongweiming/web_develop' is available! You currently
==> default: have version '0.X'. The latest is version '0.Y'. Run
==> default: `vagrant box update` to update.
```

## 下载Telegram中文版环境搭建和设置
在书中，为了减少篇幅，书中直接使用笔者配置好的环境，屏蔽了整个环境搭建和设置的过程，也没有提及这样选择的原因做详细的说明，本节将给读者从新安装的系统开始，全面和细致的给读者展示这个过程。
首先你应该已经安装好Ubuntu 16.04 LTS发行版，我们先以root账号登录，如果已经有非root，有sudo权限的其他用户也可以。

创建ubuntu用户，如果系统还没有用户可以创建它：
```
# adduser ubuntu
```
最小化的系统中默认没有安装sudo，如果发现系统没有sudo命令，安装它：
```
# apt-get install sudo

```
可以看到可以自由的在root和ubuntu这2个用户之前切换了，之后的设置都将在ubuntu这个用户下进行。顺便提一下，日常开发等操作不要使用root用户，权限太大，容易误操作。



## 主要特性

* 基于`Auth`验证的权限管理系统
    * 支持无限级父子级权限继承，父级的管理员可任意增删改子级管理员及权限设置
    * 支持单管理员多角色
    * 支持管理子级数据或个人数据
* 强大的一键生成功能
    * 一键生成CRUD,包括控制器、模型、视图、JS、语言包、菜单、回收站等
    * 一键压缩打包JS和CSS文件，一键CDN静态资源部署
    * 一键生成控制器菜单和规则
    * 一键生成API接口文档
* 完善的前端功能组件开发
    * 基于`AdminLTE`二次开发
    * 基于`Bootstrap`开发，自适应手机、平板、PC
    * 基于`RequireJS`进行JS模块管理，按需加载
    * 基于`Less`进行样式开发
* 强大的插件扩展功能，在线安装卸载升级插件
* 通用的会员模块和API模块
* 共用同一账号体系的Web端会员中心权限验证和API接口会员权限验证
* 二级域名部署支持，同时域名支持绑定到应用插件
* 多语言支持，服务端及客户端支持
* 支持大文件分片上传、剪切板粘贴上传、拖拽上传，进度条显示，图片上传前压缩
* 支持表格固定列、固定表头、跨页选择、Excel导出、模板渲染等功能
* 强大的第三方应用模块支持([CMS](https://www.fastadmin.net/store/cms.html)、[博客](https://www.fastadmin.net/store/blog.html)、[知识付费问答](https://www.fastadmin.net/store/ask.html)、[在线投票系统](https://www.fastadmin.net/store/vote.html)、[B2C商城](https://www.fastadmin.net/store/shopro.html)、[B2B2C商城](https://www.fastadmin.net/store/wanlshop.html))
* 支持CMS、博客、知识付费问答无缝整合[Xunsearch全文搜索](https://www.fastadmin.net/store/xunsearch.html)
* 第三方小程序支持([CMS小程序](https://www.fastadmin.net/store/cms.html)、[预订小程序](https://www.fastadmin.net/store/ball.html)、[问答小程序](https://www.fastadmin.net/store/ask.html)、[点餐小程序](https://www.fastadmin.net/store/unidrink.html)、[B2C小程序](https://www.fastadmin.net/store/shopro.html)、[B2B2C小程序](https://www.fastadmin.net/store/wanlshop.html)、[博客小程序](https://www.fastadmin.net/store/blog.html))
* 整合第三方短信接口(阿里云、腾讯云短信)
* 无缝整合第三方云存储(七牛云、阿里云OSS、又拍云)功能，支持云储存分片上传
* 第三方富文本编辑器支持(Summernote、Kindeditor、百度编辑器)
* 第三方登录(QQ、微信、微博)整合
* 第三方支付(微信、支付宝)无缝整合，微信支持PC端扫码支付
* 丰富的插件应用市场

## 安装使用

https://doc.fastadmin.net

## 在线演示

https://demo.fastadmin.net

用户名：admin

密　码：123456

提　示：演示站数据无法进行修改，请下载源码安装体验全部功能

## 界面截图
![控制台](https://images.gitee.com/uploads/images/2020/0929/202947_8db2d281_10933.gif "控制台")

## 问题反馈

在使用中有任何问题，请使用以下联系方式联系我们

交流社区: https://ask.fastadmin.net

QQ 1 群（满）、QQ 2 群（满）、QQ 3 群（满）、QQ 4 群（满）、QQ 5 群（满）、QQ 6 群（满）、[QQ 7 群](https://www.fastadmin.net/goto/qun)。

Github: https://github.com/karsonzhang/fastadmin

Gitee: https://gitee.com/karson/fastadmin

## 特别鸣谢

感谢以下的项目,排名不分先后

ThinkPHP：http://www.thinkphp.cn

AdminLTE：https://adminlte.io

Bootstrap：http://getbootstrap.com

jQuery：http://jquery.com

Bootstrap-table：https://github.com/wenzhixin/bootstrap-table

Nice-validator: https://validator.niceue.com

SelectPage: https://github.com/TerryZ/SelectPage

Layer: https://layuion.com/layer/

DropzoneJS: https://www.dropzonejs.com


## 版权信息

FastAdmin遵循Apache2开源协议发布，并提供免费使用。

本项目包含的第三方源码和二进制文件之版权信息另行标注。

版权所有Copyright © 2017-2022 by FastAdmin (https://www.fastadmin.net)

All rights reserved。

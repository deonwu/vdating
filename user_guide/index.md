---
layout: page
title: "测试页面"
description: "测试页面"
---

#淘点开放API手册#

淘点开放API是利用Dubbo, Spring开放的API接口。可以任何语言通过HTTP的方式调用。对于淘点的内部项目
和外部第三方开放者都使用统一的接口。

例如：

```php 

$api = new Taodian();
$api->cms_api_info();

class XX{
	function test(){
		print $api;
	}
}

```


#如何开发一个新的API#

##创建一个新的API##


*  Java基础学习
*  学习Maven, ant
*  Dubbo 框架学习
*  Spring 学习资料


##如何本地测试API##

###手动测试###

*  编译一个代码
*  设置测试环境变量
*  运行测试脚本

###自动化测试###
*  robot代码


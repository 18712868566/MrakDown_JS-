[TOC]

编写Ajax -1
===========

>创建ajax对象
>- ```ActiveXObiect("MicrosOft.XMLHTTP")```
>- ```MXLHttpRequest()；```

>链接服务器
>- ```open(方法，地址，异步传输)```
>- 同步和异步

> 发送请求
>- 同步 --- 多事件 --- js --- 事情一件一件处理
>- 异步 --- 多事件一件一件来 --- js --- 一起处理

编写Ajax -2
==========

>请求状态控制
>- ```onreadystatechage 事件```
>- ``` readyState属性： 请求状态 ```
>>- 0：未初始化）还没有调用**open()**方法 
>>- 1:(载入)已调用send()方法，正在发送请求
>>- 2:(载入完成)sned()方法完成，已收到全部相应内容
>>- 3:(解析)正在解析响应内容	
>>- 4:(完成)响应内容解析完成，可以在客户端调用了

> >> status属性：请求结果
> >> responseText


Ajax原理和步骤
============

>###例：打电话的时候
>>- 1、手机
>- 2、拨号 ---- 建立连接
>- 3、说
>- 4、听

> ###Ajax
>>- 1、创建ajax对象
>- 2、链接到服务器
>- 3、告诉服务器要什么文件，  ------  发送请求
>- 4、接受返回值





















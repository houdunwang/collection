# 集合 

Collection 组件提供一个流畅、方便的封装来操作数据。
登录 [GITHUB](https://github.com/houdunwang/mail)  查看源代码

[TOC]
# 开始使用

####安装组件
使用 composer 命令进行安装或下载源代码使用。

```
composer require houdunwang/collection
```
> HDPHP 框架已经内置此组件，无需要安装

####创建对象
```
$obj = new \houdunwang\collection\Collection();
```

####建立集合
使用对象创建
```
$collection = $obj->make([1, 2, 3]);
```

使用函数创建
```
$collection = collect([1, 2, 3]);
```

####集合数据转为数组
```
$obj->make([1, 2, 3])->toArray();
```
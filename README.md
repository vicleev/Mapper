# MyBatis 通用 Mapper4

[![Build Status](https://travis-ci.org/abel533/Mapper.svg?branch=master)](https://travis-ci.org/abel533/Mapper)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/tk.mybatis/mapper/badge.svg)](https://maven-badges.herokuapp.com/maven-central/tk.mybatis/mapper)
[![Dependency Status](https://www.versioneye.com/user/projects/593212c722f278006540a1d1/badge.svg?style=flat)](https://www.versioneye.com/user/projects/593212c722f278006540a1d1)

通用Mapper都可以极大的方便开发人员。可以随意的按照自己的需要选择通用方法，还可以很方便的开发自己的通用方法。

极其方便的使用MyBatis单表的增删改查。

支持单表操作，不支持通用的多表联合查询。

## Mapper3 拆接口，Mapper4 拆项目

## 新书《MyBatis 从入门到精通》

![MyBatis 从入门到精通](https://github.com/mybatis-book/book/raw/master/book.png)

购买地址：[京东](https://item.jd.com/12103309.html)，[当当](http://product.dangdang.com/25098208.html)，[亚马逊](https://www.amazon.cn/MyBatis从入门到精通-刘增辉/dp/B072RC11DM/ref=sr_1_18?ie=UTF8&qid=1498007125&sr=8-18&keywords=mybatis)

CSDN博客：http://blog.csdn.net/isea533/article/details/73555400

GitHub项目：https://github.com/mybatis-book/book

## 通用 Mapper 支持 Mybatis-3.2.4 及以上版本
## 不是表中字段的属性必须加 `@Transient` 注解


## 项目文档

### https://mapperhelper.github.io

在你打算使用通用 Mapper 前，一定要看看下面的文档，许多人在初次使用时遇到的问题，99% 都在文档中有说明！！

1. [如何集成通用Mapper](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/2.Integration.md)
2. [如何使用通用Mapper](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/3.Use.md)
2. [3.3.0版本新增功能用法文档](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/3.2.Use330.md)
3. [根据需要自定义接口](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/4.Professional.md)
4. [Mapper3通用接口大全](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/5.Mappers.md)
5. [扩展通用接口](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/6.MyMapper.md)
6. [使用Mapper专用的MyBatis生成器插件](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/7.UseMBG.md)
7. [在Spring4中使用通用Mapper](http://git.oschina.net/free/Mapper2/blob/master/wiki/mapper/4.Spring4.md)
8. [Mapper3常见问题和用法](http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/9.QA.md)


## 使用 Maven
```xml
<dependency>
    <groupId>tk.mybatis</groupId>
    <artifactId>mapper</artifactId>
    <version>最新版本</version>
</dependency>
```
如果你使用 Spring Boot 可以直接引入：
```xml
<!--mapper-->
<dependency>
    <groupId>tk.mybatis</groupId>
    <artifactId>mapper-spring-boot-starter</artifactId>
    <version>最新版本</version>
</dependency>
```
具体用法可以参考：[MyBatis-Spring-Boot](https://github.com/abel533/MyBatis-Spring-Boot) 

## [更新日志](http://git.oschina.net/free/Mapper/blob/master/wiki/Changelog.md)

## 作者信息

MyBatis 工具网站:[http://mybatis.tk](http://www.mybatis.tk)

作者博客：http://blog.csdn.net/isea533

作者邮箱： abel533@gmail.com

如需加群，请通过 http://mybatis.tk 首页按钮加群。

推荐使用Mybatis分页插件:[PageHelper分页插件](https://github.com/pagehelper/Mybatis-PageHelper)
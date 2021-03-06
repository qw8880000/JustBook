
星智居入门
=====================================

```
服务器后端
    |
    |-- 基本概念
    |   |
    |   |
    |   |-- cache
    |   |   |
    |   |   \-- ehcache
    |   |       |
    |   |       |-- 提供数据缓存与文件缓存功能
    |   |       \-- [ehcache](http://www.ehcache.org/)
    |   |
    |   |-- JPA(Java Persistence API)
    |   |   |
    |   |   \-- 是Sun官方提出的Java持久化规范。它为Java开发人员提供了一种对象/关联映射工具来管理Java应用中的关系数据
    |   |
    |   |-- ORM框架
    |   |
    |   |-- JSON Web Token (JWT)
    |   |   |
    |   |   |-- [基于JWT(Json Web Token)的授权方式](http://www.cnblogs.com/grissom007/p/6294746.html)
    |   |   \-- [JSON Web Token (JWT) 简介](https://mozillazg.github.io/2015/06/hello-jwt.html)
    |   |
    |   |-- sevlet容器
    |   |   |
    |   |   \-- Servlet（Server Applet），全称Java Servlet。是用Java编写的服务器端程序
    |   |
    |   |-- url
    |   |   |
    |   |   \-- url 中的#号
    |   |       |
    |   |       |-- [angular.js 前端路由](http://www.runoob.com/angularjs/angularjs-routing.html)
    |   |       |-- [URL中“#” “？” &“”号的作用](http://www.cnblogs.com/kaituorensheng/p/3776527.html)
    |   |       \-- [URL的井号](http://www.ruanyifeng.com/blog/2011/03/url_hash.html)
    |   |
    |   |-- uri
    |   |   |
    |   |   \-- 统一资源标识符（英语：Uniform Resource Identifier，或URI）是一个用于标识某一互联网资源名称的字符串
    |   |
    |   |-- json
    |   |     |
    |   |     \-- [json语法](http://www.w3school.com.cn/json/json_syntax.asp)
    |   |
    |   |-- HTTP
    |   |     |
    |   |     |-- [http 协议压缩与解压](http://kb.cnblogs.com/page/163781/)
    |   |     \-- [http协议教程](http://www.runoob.com/http/http-messages.html)
    |   |
    |   |-- [Web服务器、应用程序服务器、HTTP服务器区别](http://www.admin10000.com/document/10377.html)
    |   |
    |   |-- war
    |   |
    |   \-- RESTful api
    |           |
    |           |-- Representational State Transfer，又称具象状态传输
    |           \-- [restful api 设计指南](http://www.ruanyifeng.com/blog/2014/05/restful_api.html)
    |
    |-- spring
    |   |
    |   |-- [Spring 教程](https://www.w3cschool.cn/wkspring/index.html)
    |   |-- [Spring 教程](http://wiki.jikexueyuan.com/project/spring/)
    |   \-- [spring core](https://www.tutorialspoint.com/spring/index.htm)
    |
    |-- spring cloud 
    |   |
    |   \-- https://eacdy.gitbooks.io/spring-cloud-book/content/2%20Spring%20Cloud/2.1.1%20Eureka.html
    |
    |-- spring boot 
    |   |
    |   |-- [spring boot 官网](https://projects.spring.io/spring-boot/)
    |   |
    |   |-- [spring boot 教程 -- gitbook](https://qbgbook.gitbooks.io/spring-boot-reference-guide-zh/content/)
    |   |-- [Spring Boot开发：从0到1 -- kotlin中国](https://kotlintc.com/articles/191)
    |   |-- [springboot学习笔记 -- github](https://github.com/zsl131/spring-boot-test)
    |   |-- [Spring Boot快速入门 -- DD程序猿]( http://blog.didispace.com/spring-boot-learning-1/ )
    |   |
    |   |-- [使用Intellij中的Spring Initializr来快速构建Spring Boot/Cloud工程]( http://blog.didispace.com/spring-initializr-in-intellij/ )
    |   |
    |   |-- [Spring MVC 解读——@RequestMapping 1](https://my.oschina.net/HeliosFly/blog/212329)
    |   |
    |   |-- 创建可执行jar
    |   |   |
    |   |   \-- spring-boot-gradle-plugin
    |   |
    |   |-- spring boot Junit单元测试
    |   |   |
    |   |   \-- [Spring Boot Junit单元测试](https://yq.aliyun.com/articles/6925)
    |   |
    |   |
    |   |
    |   \-- 常用注解
    |       |
    |       |-- [使用SpringMVC注解@RequestParam(value="XXX",required=false)时需要注意的问题](http://blog.csdn.net/hellostory/article/details/7519358)
    |       |
    |       |-- @RestController
    |       |-- @EnableAutoConfiguration
    |       |-- @ComponentScan
    |       |-- @Autowired
    |       \-- @SpringBootApplication
    |
    |
    |-- Swagger2 
    |   |
    |   |-- [Spring Boot中使用Swagger2构建强大的RESTful API文档](http://blog.didispace.com/springbootswagger2/)
    |   \-- 是一个规范和完整的框架，用于生成、描述、调用和可视化 RESTful 风格的 Web 文档
    |
    |-- docker
    |   |
    |   \-- [docker 教程](https://yeasy.gitbooks.io/docker_practice/content/)
    |   
    |   
    |-- jenkins   
    |   |
    |   |-- 持续集成引擎
    |   \-- [入门手册](http://files.cnblogs.com/files/zz0412/jenkins%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.pdf)
    |
    |
    |-- gradle
    |
    |
    |-- database
    |   |
    |   \-- mongodb
    |       |
    |       |-- [mongodb docs](https://docs.mongodb.com/)
    |       |-- [mongodb manual docs](https://docs.mongodb.com/manual/?_ga=2.144241781.1997094620.1503452776-1411300187.1503452776)
    |       \-- [mongoose docs](http://mongoosejs.com/docs/index.html)
    |
    |-- 问题
    |   |
    |   |-- onkeypress="return (/[\d]/.test(String.fromCharCode(event.keyCode)))"
    |   |   |
    |   |   |-- [HTML onkeypress 事件属性](http://www.runoob.com/tags/ev-onkeypress.html)
    |   |   \-- [JavaScript 正则表达式](http://www.runoob.com/js/js-regexp.html)
    |   |
    |   |-- @Restcontroller所对应的gradle依赖
    |   |   |
    |   |   \-- [spring-boot-starter-*]( https://qbgbook.gitbooks.io/spring-boot-reference-guide-zh/content/III.%20Using%20Spring%20Boot/13.5.%20Starters.html )
    |   |   
    |   \-- 链接如何对应到一个类中的方法(实现原理)
    |
    |-- 开发工具
    |   |
    |   |-- idea
    |   \-- webstrom
    |
    |-- nginx
    |   |
    |   |-- [nginx 配置指南](http://nginx.org/en/docs/beginners_guide.html)
    |   |-- [nginx config 指令](http://nginx.org/en/docs/http/ngx_http_core_module.html#directives)
    |   \-- [nginx 指南](https://www.ctolib.com/docs-nginx-c-index.html)
    |
    |
    |-- webpack
    |   |
    |   |
    |   |-- source map
    |   |   |
    |   |   |-- [JavaScript Source Map 详解](http://www.ruanyifeng.com/blog/2013/01/javascript_source_map.html)
    |   |   \-- [[webpack] devtool配置对比](http://www.cnblogs.com/hhhyaaon/p/5657469.html)
    |   |
    |   \-- [webpack 中文](https://doc.webpack-china.org/)
    |
    |-- node.js
    |   |
    |   |-- 教程
    |   |   |
    |   |   |-- [node.js 中文网](http://nodejs.cn/api/path.html)
    |   |   |-- [node.js api 文档](http://nodejs.cn/api/modules.html)
    |   |   |-- [node 入门](https://www.nodebeginner.org/index-zh-cn.html)
    |   |   |
    |   |   |-- [node.js 学习路线图](http://www.open-open.com/lib/view/open1403574545233.html)
    |   |   |
    |   |   \-- 《node.js 开发指南》
    |   |       |
    |   |       |-- node.js是什么？
    |   |       |-- 异步式 I/O 与事件驱动
    |   |       |-- javascript的高级特性:作用域，闭包，对象
    |   |       \-- node.js 编程规范
    |   |
    |   |-- tips
    |   |   |
    |   |   |
    |   |   \-- exports 与 module.exports的区别
    |   |       |-- module 与 exports 是node.js里的两个全局对象
    |   |       |-- module.exports 说明module有一个属性叫exports
    |   |       |-- 初始时 module.exports = exports = {} ，即module.exports与exports引用同一个对象
    |   |       |-- var n = require('test.js') 等于 var n = module.exports，即最终使用的是module.exports指向的对象
    |   |       \-- 如果改变module.exports引用的对象，则exports失效
    |   |
    |   |-- promise
    |   |   |
    |   |   |-- [promise](http://liubin.org/promises-book/)
    |   |   |-- [promise 简单实现](https://www.promisejs.org/implementing/)
    |   |   |-- [promise 简单实现](http://www.tuicool.com/articles/fe6Jbyz)
    |   |   |-- [promise 简单实现](https://segmentfault.com/a/1190000003028634)
    |   |   |-- [Promise对象](http://javascript.ruanyifeng.com/advanced/promise.html)
    |   |   \-- [bluebird与原生Promise对象及bluebird模块的中文API文档](https://itbilu.com/nodejs/npm/VJHw6ScNb.html#api-then)
    |   |
    |   |
    |   |-- lodash
    |   |   |
    |   |   |-- [lodash 中文文档](https://wizardforcel.gitbooks.io/lodash-doc-45/content/)
    |   |   \-- [lodash 中文文档](http://lodashjs.com/docs/)
    |   |
    |   |-- express
    |   |   |
    |   |   |
    |   |   \-- [express 中文官网](http://www.expressjs.com.cn/)
    |   |
    |   |
    |   |-- pm2
    |   |   |
    |   |   \-- [Nodejs学习笔记（十三）— PM2](http://www.cnblogs.com/zhongweiv/p/pm2.html)
    |   |
    |   |-- bower
    |   |   |
    |   |   |-- 为前端而生
    |   |   |-- [bower -- github](https://github.com/bower/bower)
    |   |   \-- [bower简明入门教程](https://segmentfault.com/a/1190000002971135)
    |   |
    |   \-- grunt
    |       |
    |       |-- [【grunt整合版】30分钟学会使用grunt打包前端代码](http://www.cnblogs.com/yexiaochai/p/3603389.html)
    |       |
    |       |-- grunt 拆分
    |       |
    |       \-- 重要的文件
    |           |
    |           |-- Gruntfile.js
    |           \-- package.json
    |
    |-- JavaScript
    |   |
    |   |-- javascript 与 ECMAScript  
    |   |   |
    |   |   |-- [ES5, ES6, ES2016, ES.Next: JavaScript 的版本是怎么回事？「译」](https://huangxuan.me/2015/09/22/js-version/)
    |   |   \-- 现实中我们只用 ECMAScript 称呼标准，平时都还是使用 JavaScript 来称呼这个语言
    |   |
    |   |-- 函数式编程
    |   |
    |   |-- [Javascript 严格模式 "" ](http://www.ruanyifeng.com/blog/2013/01/javascript_strict_mode.html)
    |   |-- [JavaScript this](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Operators/this)
    |   |-- [JavaScript 闭包](http://www.ruanyifeng.com/blog/2009/08/learning_javascript_closures.html)
    |   \-- [JavaScript 闭包](http://www.runoob.com/js/js-function-closures.html)
    |
    \-- java
        |
        |-- [关于依赖注入](https://martinfowler.com/articles/injection.html)
        |
        |-- 泛型( Generic type ) 
        |   |
        |   |-- [Java总结篇系列：Java泛型](http://www.cnblogs.com/lwbqqyumidi/p/3837629.html)
        |   |-- [Java泛型详解](https://www.ziwenxie.site/2017/03/01/java-generic/)
        |   \-- [java 泛型详解（普通泛型、 通配符、 泛型接口）](http://iteye.blog.163.com/blog/static/18630809620131472312201/)
        |
        |-- java 注解
        |       |
        |       |
        |       |-- [The Java Annotation Tutorial](https://docs.oracle.com/javase/tutorial/java/annotations/index.html)
        |       |-- http://wiki.jikexueyuan.com/project/java-reflection/java-at.html
        |       \-- http://www.importnew.com/10294.html
        |
        |-- java 反射
        |       |
        |       \-- http://wiki.jikexueyuan.com/project/java-reflection/
        |
        \-- bean

```

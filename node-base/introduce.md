### nodejs

nodejs就像我们的浏览器一样可以对web项目中的js文件进行解析（在浏览器中有专门处理js文件的js引擎，现在最强大的就是V8，而nodejs使用的也是这个引擎）。

每一种js解析器都是一个运行环境，不但允许js定义各种数据结构，还允许js使用该运行环境提供的内置对象和方法。我们知道像浏览器提供了像document之类的内置对象，我们使用js可以进行各种dom操作；NodeJS也提供了fs（操作磁盘文件），http（搭建http服务器）
等对象。

在Nodejs中实现的是模块化的开发，每一个文件就是一个模块（module），由于开发中可能会有很多模块，我们需要对这些模块进行管理，所以出现了包（package）这个概念，在项目的开发中为了实现快速开发，我们可以引用第三方的包，而nodejs刚好有一个生态圈npm，我们可以使用npm命令下载第三方包，也可以上传自己的第三方包。所以在nodejs中我们需要了解的就是模块，包，npm这三个东西。

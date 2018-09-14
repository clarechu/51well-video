# 51well-video

项目名称: 51weel-video

## 环境的安装

1. webpack-cli 安装

```shell
# 使用npm（需要安装node环境）全局安装webpack，打开命令行工具输入：
npm install webpack -g
# 或者（npm install -g webpack），
# 安装完成之后输入 webpack -v，如下图，如果出现相应的版本号，则说明安装成功。
```

用vue-cli来构建项目

```shell
vue init webpack 51well-video
```

输入命令后，会跳出几个选项让你回答：

* Project name (baoge)： -----项目名称，直接回车，按照括号中默认名字（注意这里的名字不能有大写字母，如果有会报错Sorry, name can no longer contain capital letters），阮一峰老师博客为什么文件名要小写 ，可以参考一下。

* Project description (A Vue.js project)： ----项目描述，也可直接点击回车，使用默认名字

* Author ()： ----作者，输入你的大名

接下来会让用户选择：

* Runtime + Compiler: recommended for most users 运行加编译，既然已经说了推荐，就选它了.

* Runtime-only: about 6KB lighter min+gzip, but templates (or any Vue-specificHTML) are ONLY allowed in .vue files - render functions are required elsewhere 仅运行时，已经有推荐了就选择第一个了

* Install vue-router? (Y/n) 是否安装vue-router，这是官方的路由，大多数情况下都使用，这里就输入“y”后回车即可。

* Use ESLint to lint your code? (Y/n) 是否使用ESLint管理代码，ESLint是个代码风格管理工具，是用来统一代码风格的，一般项目中都会使用。

* 接下来也是选择题Pick an ESLint preset (Use arrow keys) 选择一个ESLint预设，编写vue项目时的代码风格，直接y回车

* Setup unit tests with Karma + Mocha? (Y/n) 是否安装单元测试，我选择安装y回车

* Setup e2e tests with Nightwatch(Y/n)? 是否安装e2e测试 ，我选择安装y回车s
  
> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

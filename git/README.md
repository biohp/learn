# 两客一危

> 一个Vue.js项目

## 构建步骤

``` bash
# 安装依赖关系
npm install

# 在8080端口进行热加载
npm run dev

# 打包上线
npm run build
```

## 技术栈

vue2 + vuex + vue-router + webpack + ES6/7 + axios 

## 目录结构
* node_modules		项目依赖 
* src
	* assets	资源，存放公共img,js,css等等
	* common	公共数据
	* components	公共组件
	* layouts	页面布局
	* services	api管理
	* store		vuex数据管理
	* utils		工具包
	* views		视图页面
	* App.vue
	* main.js 	项目入口
	* router.js 	路由配置信息
* .babelrc		es6解析es5配置信息
* .editorconfig
* .gitignore 		git上传过滤文件配置
* index.html 
* package-lock.json
* package.json 		包管理文件
* README.md
* webpack.config.js 	webpack配置信息

## 项目搭建

* 开发环境
	* node.js
	* [下载地址](https://nodejs.org/en/)
	* [安装步骤](http://www.runoob.com/nodejs/nodejs-install-setup.html)
	* 使用npm管理依赖关系	[npm使用](http://www.runoob.com/nodejs/nodejs-npm.html)
	* npm速度不佳可使用cnpm或yarn	[cnpm下载](http://npm.taobao.org/)
* 开发工具
	* git(可选项)
	* [下载地址](https://git-scm.com/)
	* [安装步骤](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137396287703354d8c6c01c904c7d9ff056ae23da865a000)
* 脚手架
	* vue-cli
	* [安装与使用方法](https://www.npmjs.com/package/vue-cli)
	* 构建项目 vue init webpack-simple myProjectName (webpack-simple 简洁版)
* UI
	* iview
	* [安装与使用方法](https://www.iviewui.com/docs/guide/install)
* 依赖
	* vuex 组件间数据交互解决方案 [使用方法](https://vuex.vuejs.org/zh-cn/installation.html)
	* vue-router 页面路由管理插件 [使用方法](https://router.vuejs.org/zh-cn/installation.html)
	* axios 异步请求插件 [使用方法](https://www.kancloud.cn/yunye/axios/234845)
	* babel-polyfill 兼容IE [使用方法](https://babeljs.io/docs/usage/polyfill/)

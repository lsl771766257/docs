#Springboot+Vue实现前后端分离
###1 Vue环境搭建
Node.js 安装，JavaScript的运行环境

npm安装（Mac下Homebrew），包管理工具

安装完node.js后打开cmd小黑窗安装淘宝镜像，用cnpm代替npm,依赖全 速度快

npm install -g cnpm --registry=https://registry.npm.taobao.org

安装webpack，Vue的组件都是通过.vue或类似微信小程序.wxml和.wxss等自定义组件无法被各种浏览器解析，需要被打包翻译成.js文件。

cnpm install webpack -g

安装vue脚手架，vue-cli用来生成模板Vue工程，相当于按照设计好的图来盖房子；微信小程序也会以可视化界面的方式问你是否创建示例工程，就是封装了类似的脚手架

npm install vue-cli -g

在硬盘上找一个文件夹放工程用的，在终端中进入该目录  ：cd 目录路径

根据模板创建项目：vue init webpack vueDemo

到 vueDemo目录下安装项目依赖：cnpm install

启动项目：cnpm run  dev

###2 Vue路由设置
如果创建好的vue项目里没有 vue-router 路由依赖需要自行添加：cnpm install vue-router --save

用 Vue.js + vue-router 创建单页应用，是非常简单的。使用 Vue.js ，我们已经可以通过组合组件来组成应用程序，当你要把 vue-router 添加进来，我们需要做的是，将组件(components)映射到路由(routes)，然后告诉 vue-router 在哪里渲染它们


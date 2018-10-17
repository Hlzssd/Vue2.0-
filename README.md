# Vue2.0-
## Vue2.0萌新快速入门 
## 安装nodejs
## node -V
## 安装webpack
## npm install webpack -g  全局安装
## 查看版本 webpack -V
## 安装Vue -
## npm install vue -g
## npm install vue-cli -g
## vue init webpack VueDemoProject

# 注意 Use ESLint to lint your code? (Y/n)  N

cd VueDemoProject
接下来就是
npm install  ||  npm i  
用淘宝镜像的
cnpm install  ||  cnpm i
下面我们启动项目
npm run dev

##### 浏览器 输入 localhost:8080
#### 成功启动项目 nice

#### 看看我们的文件夹

**build：webpack的相关配置，里边的各种命令vue脚手架已经帮我们配置好了。
**config：vue的基本配置文件，比如端口号监听，打包输出等等。
##### dist：打包后的文件都在这，也就是说你运行npm run build之后产生的一坨东西，都在这里 ，开发完后，把它们直接扔到你的web服务器上，就是上线喽。
##### src：这个才是我们的地盘，要写页面代码，请认准src牌文件夹。
##### assets：静态资源请放到这里，比如单独的css，js。
##### components：公用的组件，意思就是很多组件都会用到某一个组件，那放到这里就没错了。
##### pages： 页面组件（说人话就是.vue文件）存放的地方。
##### router：顾名思义，就是放路由的地方，配置 自己看看
##### static：图片啥的你可以放到这。
##### test：测试？暂时用不到。
##### .babelrc：es6语法编译配置，意思就是你的代码里有es6的语法，但是浏览器并不认识es6啊，就靠它给翻译一下，让浏览器认识。
##### .editorconfig：编辑器配置，emmmmmm，我也不太懂这用来干啥。
##### .gitignore：git忽略文件，提交代码的时候，告诉git，某些东西不要提交，比如node_modules文件夹，这玩意里边一大坨，总不能每次提交代码的时候等半天吧。
##### .postcssrc.js：postcss配置，你问我什么是postcss？自己查去。
##### index.html：这个不用我解释了吧，入口文件，浏览器第一眼看到的就是它。
##### package-lock.json：锁定安装时的包的版本号，说人话就是，你的npm下载了一堆依赖，如果别人在npm install的时候，会默认下载最新版本的依赖，but新的版本不一定会兼容旧的啊，那别人可能就跑不起来你的项目了，这个时候，package-lock.json出来把你的版本锁定，这样别人npm install的时候，也就只能下载和你一样的版本了。
##### package：项目的基本信息，比如项目名称，安装了哪些依赖，版本号是多少，统统在这里
----

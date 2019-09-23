# myPicture

我的相册

技术栈：vue2.0 + mintUi + axios + mock
语法：es6
功能：首页、列表页、我的

Mint UI 使用文档
http://mint-ui.github.io/docs/#/zh-cn2
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

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# 规范
1、class名称用_分隔
2、js变量用驼峰定义
3、公共组件写[/src/components]
4、当前页面组件在当前文件夹下[/components]中
5、页面中style标签需带有[scoped]，深层用 [/deep/]解决
6、图片名称用_分隔，使用当前页面名称开头，如[home_bg.png]，如果是通用图片[common_]开头, icon用[icon_]开头
7、写css、js、html模版都要有注释，越详细越好
8、请求数据都使用mock


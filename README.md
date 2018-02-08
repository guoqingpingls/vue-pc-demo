# vue-pcdemo

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

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

运行项目步骤：
本地具备node稳定版环境
01.vue init webpack you-projeck-name
02.用git上的src目录替代you-projeck的src目录
03.npm install
04.cnpm i vue-resource -S
05.cnpm i vuex -S
06.cnpm i json-server (暂时使用的是json-server模拟的后台数据)
07.将git的db.json文件复制到you-projeck根目录下
08.修改build/dev-server.js文件(具体修改查看git上相应的文件)
09.修改config/index.js文件(具体修改查看git上相应的文件)
10.执行npm run dev
注：由于json-server的post请求数据方法稍有问题，暂时全部使用get方式代替
测试

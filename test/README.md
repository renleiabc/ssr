# test

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
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
#参考网址
 https://blog.csdn.net/ligang2585116/article/details/78533793
#注意：以下文件在配置的过程中都需要修改
 build
  ├── webpack.base.conf.js  # 基础通用配置
  ├── webpack.client.conf.js  # 客户端打包配置
  └── webpack.server.conf.js  # 服务器端打包配置
  config
  ├── index.js  # 基础通用配置
 
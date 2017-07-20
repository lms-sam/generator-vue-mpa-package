## 思清音乐移动端vue单页面项目脚手架2.0.0，项目所使用的工具如下
> node -version 6.9.3

- yarn
- webpack

## How use it?
download project

    git clone git@139.196.126.103:sapling-team/generate-vue-spa2.0.git

remove git origin and add your project new origin

    git remote remove origin

    git remote add origin gitUrl

    git pull

pack install

    yarn install

we can using npm scripts start dev product test

    npm run build 打包出生产环境代码
    npm run build-dev 打包出开发环境代码
    npm run dev 启动webpack dev构建环境

## 目录结构

```
|
|----- build   脚手架配置环境
|
|
|----- config  环境配置文件
|
|
|----- dist    生产打包文件
|
|
|----- src     开发环境文件
|       |
|       |
|       |----- api         接口管理
|       |
|       |
|       |----- components  组件
|       |					|
|       |					|
|       |					|----- page   页面入口
|       |
|       |
|       |
|       |----- config      配置文件
|       |
|       |
|       |----- filter      过滤器,修改、拦截数据
|       |
|       |
|       |----- images      图片资源
|       |
|       |
|       |----- stylesheets 样式
|       |
|       |
|       |----- util        工具
|       |
|       |
|       |----- router       路由
|       |
|       |
|       |----- vuex        状态管理
|       |
|       |
|       |----- app.vue     视图总入口
|       |
|       |
|       |----- main.js     项目总入口
|
|
|----- .babelrc    babel配置
|
|
|----- .eslintrc   eslint配置
|
|
|----- .babelrc    babel配置
|
|
```
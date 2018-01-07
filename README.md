# 移动商城

> 使用有赞移动端 Vue 组件库 — [Vant](https://www.youzanyun.com/zanui/vant#/zh-CN/component/intro)



## Vue相关库与插件

- Vue + Vue-router + Vant + Sass
- axios
- vuelidation( 表单验证 )
- fastclick
- babel-polyfill
- @xkeshi/vue-countdown ( 各种倒计时 )

> 未使用Vuex, 因为各个页面有较高的独立性. 可以省下Vuex, 少部分组件通信使用 event bus 即可.


> 店铺信息: sessionStorage
>
> 用户信息及token:  localStorage

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
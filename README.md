# 随便点外卖APP
## 项目描述：vue2+webpack+es6+组件化实现的在线支付外卖app，有商品分类，商品详情，商品平分，购物车，评价分类展示，店家信息等功能。
### 所用技术：vue-cli、vue-router、betterScroll、axios等

**项目心得：**
1. 项目打包后会出现跨域问题，需要把build里的路径改一下
2. betterScroll滚动插件要在合适的时候调用，否则不生效
3. 需要用到两次以上的应该考虑写成组件，比如评分星星，购物车加减按钮
4. 父组件向子组件传值，子组件取值偶尔会出现undefined，需要加上v-if判断或者给初始值
5 .Vue报错信息较多，用Vue.js devtools这个浏览器插件来进行调试

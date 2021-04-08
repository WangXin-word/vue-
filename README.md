# vue应该了解第三方库
 
 # [core-js](https://www.npmjs.com/package/core-js)
    JavaScript的模块化标准库。包括截至2021年的ECMAScript的polyfill：承诺，符号，集合，迭代器，类型数组，许多其他功能，ECMAScript建议，一些跨平台的WHATWG / W3C功能和建议，例如URL。您可以仅加载必需的功能，也可以使用它而不会污染全局名称空间。
    开源库zloirock/core-js
    提供了es5、es6的polyfills，包括promises、symbols、collections、iterators、typed arrays、ECMAScript 7+ proposals、setImmediate 等等。
    如果使用了 babel-runtime、babel-plugin-transform-runtime 或者 babel-polyfill，你就可以间接的引入了 core-js 标准库
    
 # [echarts](https://echarts.apache.org/en/tutorial.html#Get%20Started%20with%20ECharts%20in%205%20minutes)
    Apache ECharts是一个免费的，功能强大的图表和可视化库，它提供了一种简单的方法来向您的商业产品中添加直观，交互式和高度可定制的图表。它是用纯JavaScript编写的，并基于zrender，它是一个全新的轻量级画布库。

 # [file-saver](https://www.npmjs.com/package/file-saver)
    如果您需要保存大于blob大小限制的超大文件或没有足够的RAM，请查看更高级的StreamSaver.js ，它可以利用新流的功能将数据异步异步直接保存到硬盘中。 API。这样可以支持进度，取消操作并知道何时完成编写

 # [mockjs](http://mockjs.com/)
    Mock.js是一个模拟数据生成器，可帮助前端开发和原型与后端进度分开，并减少某些单调性，尤其是在编写自动化测试时。

 # [qrcode](https://www.npmjs.com/package/qrcode)
    QR code / 2d条码生成器。

 # [vue-baidu-map](https://dafrok.github.io/vue-baidu-map/#/zh/index)
    Vue 2.x的百度地图组件

 # [vue-class-component](https://jingyan.baidu.com/article/60ccbceb05fa4125cbb19733.html)
    ECMAScript / TypeScript装饰器，用于类样式的Vue组件。
    <template>
        <div>
            <button v-on:click="decrement">-</button>
            {{ count }}
            <button v-on:click="increment">+</button>
        </div>
    </template>

    <script>
        import Vue from 'vue'
        import Component from 'vue-class-component'

        // Define the component in class-style
        @Component
        export default class Counter extends Vue {
            // Class properties will be component data
            count = 0

            // Methods will be component methods
            increment() {
                this.count++
            }

            decrement() {
                this.count--
            }
        }
    </script>
    如示例所示，您可以通过使用@Component装饰器为类添加注释，从而以直观和标准的类语法定义组件数据和方法。您可以简单地用类样式的组件替换您的组件定义，因为它等同于组件定义的普通options对象样式。

    通过以类样式定义组件，您不仅可以更改语法，还可以利用某些ECMAScript语言功能，例如类继承和装饰器。Vue类组件还提供了一个用于mixin继承的mixins助手，以及一个可以轻松创建自己的装饰器的createDecorator函数。

 # [vue-property-decorator](https://jingyan.baidu.com/article/60ccbceb05fa4125cbb19733.html)
    ue property decorator 深度依赖了 vue class component 拓展出了很多操作符 @Prop @Emit @Inject 等等 可以说是 vue class component 的一个超集
    正常开发的时候 你只需要使用 vue property decorator 中提供的操作符即可 不用再从vue class componen 引入vue component


 # [vue-router](https://router.vuejs.org/zh/)

 # [vuex](https://vuex.vuejs.org/zh/)
    state 存放状态
    mutations state成员操作
    getters 加工state成员给外界
    actions 异步操作
    modules 模块化状态管理

 # [vuex-class](https://jingyan.baidu.com/article/60ccbceb05fa4125cbb19733.html)
    绑定Vuex和vue-class-component的助手

 # [node-sass](https://jingyan.baidu.com/article/60ccbceb05fa4125cbb19733.html)

 # [sass-loader](https://www.npmjs.com/package/sass-loader)
    加载Sass / SCSS文件并将其编译为CSS。

 # [typescript](https://www.tslang.cn/docs/home.html)
 TypeScript是用于应用程序级JavaScript的语言。

 # [vue-template-compiler](https://jingyan.baidu.com/article/60ccbceb05fa4125cbb19733.html)
    该软件包可用于将Vue 2.0模板预编译为渲染函数，以避免运行时编译开销和CSP限制。在大多数情况下，应该将其与一起使用vue-loader，只有在编写具有非常特定需求的构建工具时，才需要单独使用它。

# [nprogress](https://www.npmjs.com/package/nprogress)
 Ajaxyy应用程序的细长进度条。灵感来自Google，YouTube和Medium。


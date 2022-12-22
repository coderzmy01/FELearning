![image-20221210191755666](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221210191755666.png)

在引入 Vue.js 的时候，我们可以选择不同的 Vue.js 版本。这些版本之间的主要区别在于它们是否包含了模板编译器，以及它们是否支持将模板编译为不同的语言。

Vue.js 提供了四种不同的版本：

- runtime-only：这是最小的 Vue.js 版本，它不包含模板编译器，只包含了运行时的 Vue.js 库。这种版本适用于将模板预编译为渲染函数的开发者，或者在浏览器中直接使用已经编译好的渲染函数。
- runtime + compiler：这是一个完整的 Vue.js 版本，包含了运行时库和模板编译器。它允许开发者在运行时将模板编译为渲染函数，这对于开发复杂应用时非常方便。
- standalone：这是一个独立的 Vue.js 版本，包含了运行时库和模板编译器，并且暴露了一些额外的全局变量，比如 `Vue` 和 `Vuex`。这种版本适用于将 Vue.js 作为一个库来引入到其他项目中。
- esm-browser：这是一个支持 ECMAScript 模块的 Vue.js 版本，包含了运行时库和模板编译器。它可以通过使用 `import` 和 `export` 语句来引入和导出 Vue.js 中的组件和
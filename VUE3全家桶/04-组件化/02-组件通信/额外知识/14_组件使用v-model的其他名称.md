---
title: 组件的v-model
tag: #literature #前端/vue 
time: 2022-12-18 
---
#literature #前端/vue 
## 需求
- 自定义v-model 的属性

v-model 在组件中使用，其实和props传递的很像，前面加v-model:

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218211218.png)

emits事件则是加上 `update:name` 

## 方案



## 引用

### 绑定 v-model[#](https://vue3.chengpeiquan.com/communication.html#%E7%BB%91%E5%AE%9A-v-model-new)

> 注：这一小节的步骤是在 Father.vue 里操作。

和下发 props 的方式类似，都是在子组件上绑定 Father.vue 定义好的数据，这是绑定一个数据的例子：

vue

```vue
<!-- Father.vue -->
<template>
  <Child v-model:username="userInfo.name" />
</template>
```

和 Vue 2 不同， Vue 3 可以直接绑定 v-model ，而无需在子组件指定 [model 选项](https://v2.cn.vuejs.org/v2/api/#model) ，并且 Vue 3 的 v-model 需要使用英文冒号 `:` 指定要绑定的属性名，同时也支持绑定多个 v-model 。

如果要绑定多个数据，写多个 v-model 即可：

vue

```vue
<!-- Father.vue -->
<template>
  <Child
    v-model:uid="userInfo.id"
    v-model:username="userInfo.name"
    v-model:age="userInfo.age"
  />
</template>
```

看到这里应该能明白了，一个 v-model 其实就是一个 prop ，它支持的数据类型和 prop 是一样的，所以子组件在接收数据的时候，完全按照 props 去定义就可以了。

点击回顾：[接收 props](https://vue3.chengpeiquan.com/communication.html#%E6%8E%A5%E6%94%B6-props) ，了解在 Child.vue 如何接收 props，以及相关的 props 类型限制等部分内容。





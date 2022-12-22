---
title: keep-alive组件
tag: #literature #前端/vue 
time: 2022-12-18 {{time}}
---
#literature #前端/vue 
## 需求

- 希望一个组件不会被频繁的卸载再重新创建；keep-alive保持存活；

例子：
```js
counter 计数器每次打开都要重新计数
```

- 希望**特定**的组件能够被keep-alive

`include:name`
需要在组件中定义一个name属性
可以使用`exclude`来排除


## 原理

进行缓存，不会被销毁掉

### 缓存组件的生命周期

- `activated()
- `deativated()`



## 引用

认识keep-alive

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218165919.png)


keep-alive属性

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218170049.png)


缓存组件的生命周期

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218170136.png)





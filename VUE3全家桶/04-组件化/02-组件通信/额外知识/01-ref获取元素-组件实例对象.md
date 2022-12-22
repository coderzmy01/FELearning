#literature #前端/vue 

## ref的基本使用
- 需求：获取原生DOM元素
错误的操作：qs获取dom,改变元素
**一定要这么做** 通过ref,让vue来获取这个元素


## 获取组件实例

在父组件ref绑定子组件的实例对象，可以调用该子组件的内部方法

获取子组件的元素`$el` ,如果是单个结点，直接获取该节点，当有多个根时，返回第一个node结点
`this.$refs.element.$el`

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218123742.png)

## $parent $root





## 引用

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218124315.png)


![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218124359.png)


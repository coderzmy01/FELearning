## 1. 定义

非props的attribute的是指在父组件传入了在子组件没有定义的属性

## 2. 处理方式

会将属性添加到根节点的Attribute中

![image-20221212142406037](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221212142406037.png)



### 禁用和使用

- inheritAttrs:false
- $attr来访问

![image-20221212142549581](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221212142549581.png)



- 多个根

![image-20221212143011950](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221212143011950.png)
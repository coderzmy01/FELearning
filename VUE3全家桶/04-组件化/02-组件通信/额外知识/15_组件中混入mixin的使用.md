---
title: 组件中的mixin
tag: #literature #前端/vue  
time: 2022-12-18 
---
#literature #前端/vue  
## 需求

 组件和组件之间有相同的代码逻辑，希望对相同的代码逻辑进行抽取。

举一个例子
home,about,banner,有一部分重复代码，我想要把这些代码给抽取出来


## 方案

1. 创建mixin模块，导出对象
2. 在options API 添加 mixin，并添加这个属性
3. 使用规则
	1. 都有data的返回对象;
		1. 合并
		2. 以组件中的为主
	2. 生命周期钩子函数
		1. 都会合并到数组中，然后被调用
	3. 值为对象选项如`method` 被合并做一个对象
			1. 定义的方法都会生效
			2. 以组件中的为主


4. 全局混入：在`app.mixin` 注册

## 引用

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218214917.png)

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218214934.png)


![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218214950.png)




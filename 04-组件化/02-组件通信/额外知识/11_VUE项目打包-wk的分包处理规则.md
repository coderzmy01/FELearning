---
title: VUE项目打包
tag: #literature #前端/vue 
time: 2022-12-18 {{time}}
---
#literature #前端/vue 
## 需求

- 提升用户的首屏渲染速度

旧方案：
1. 解析每个页面的css、html、js ,之后开始渲染
2. 每个页面的逻辑复杂，代码量大，导致首屏空白

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218173601.png)

$$ 打包文件夹分析与部署$$

-  单独打包一个文件


## 方案

`import函数` 来使wk对其进行分包处理

## 引用

![image.png](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/20221218185537.png)







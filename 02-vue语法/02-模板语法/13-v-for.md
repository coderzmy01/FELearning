## 1. 列表渲染

![image-20221204153023308](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221204153023308.png)



## 2. 基本使用

![image-20221204153110665](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221204153110665.png)



## 3. 支持类型

![image-20221204154507603](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221204154507603.png)

- 也可以遍历数字



## 4. 数组更新检测

![image-20221204155143190](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221204155143190.png)



## 5. key的作用

![image-20221205165620789](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221205165620789.png)



### 1. VNode

- virtual node ,虚拟节点
- vnode 的本质还是一个js对象，可以理解从template中过渡到真实dom

![image-20221205170244373](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221205170244373.png)

### 2. 虚拟DOM

- 当一大堆元素嵌套起来的时候，就形成的Vnode Tree,而这个结构就是虚拟dom

![image-20221205171057428](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221205171057428.png)

- 优点

  - 可以跨平台开发，虚拟DOM会根据不同的开发环境去找到的对应渲染方式，

  ![image-20221205171157162](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221205171157162.png)



- 尽可能复用可以复用的结点

![image-20221205181345361](https://finzulpic.oss-cn-hangzhou.aliyuncs.com/image-20221205181345361.png)
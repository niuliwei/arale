
康辉负责

## overview
目前的想法是整个组件分为3部分. 

1. base widget核心. 负责整个widget的构成和处理
2. view 展现模块. 其中主要是模板的渲染(data+css+tpl)
3. Model 数据存储. 其中可以进行扩展, 比如Model本身可以从服务器端获取数据, 也可以从本地存储获取数据,然后也可以进行缓存. 其中对外提供统一的接口进行数据的获取和设置.

### 属性
1. 
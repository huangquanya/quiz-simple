# JS 使用和基本编程

## 写代码

请完成以下文件中的编码需求：

- [查看 `clone.js`](./clone.js)
- [查看 `get-host.js`](./get-host.js)
- [查看 `get-sum.js`](./get-sum.js)

## 方法论

如果你有一定的开发经验，并且追求代码的质量。  
那么你一定知道一些实践技巧，简答 3 ～ 10 条即可。

例如：

> 面向对象编程，代码逻辑可以内聚。
> 禁止使用 var，不可变数据用 const 声明，可变数据用 let 声明。

答:
html标签尽量使用语义化标签便于提高SEO
css命名使用BEM风格，避免命名冲突导致bug
css类名语义化，便于代码review
css标签顺序先布局再细节，样式从外到内，从左到右，从上到下
react 在编写时分为无状态组件和有状态组件
## 请问以下代码做了什么事情

```js
const getLoglevel = () => {
  return localStorage.loglevel ?? 'INFO';
};
```

答：
向localStorage中查询loglevel字段，查询不到则将其赋值为'INFO'
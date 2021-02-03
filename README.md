# Llab
> 做一些奇奇怪怪的`小测试 `

---
## Js双击按钮系列
- 双击执行操作
- 双击和单击都会执行操作
- 单击双击，防止误触发
### 1.双击并执行操作  
总的来说，很简单，给了一个内置函数，但是也有很多缺陷，稍后我会继续脑洞思考  

```js
object.ondblclick=function(){SomeJavaScriptCode}
```

### 2.双击和单击都会执行操作
如果想让一个  DOM  对象既可以被单击，也可以被双击，可以在该对象上同时绑定单击（ click ）和双击（ dblclick ）事件。  
```js
element.addEventListener(event, function, useCapture)
```
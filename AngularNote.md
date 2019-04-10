## 多路由模块
生成一个带路由的模块
```language
ng g module name --routing
```
**路由模块匹配顺序** 
每个路由模块都会根据导入的顺序把自己的路由配置追加进去

## Observable可观察者对象
### 观察者回调函数

Observables 与 Observer 之间的订阅发布关系(观察者模式) 如下：

订阅：Observer 通过 Observable 提供的 subscribe() 方法订阅 Observable。
发布：Observable 通过回调 next 方法向 Observer 发布事件。
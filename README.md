## study-jquery
### 基础
* 自调用匿名函数
  * 创建一个新的函数作用域
  * 确保jquery代码不被其他代码干扰
  * 防止jquery污染全局
* jquery将window对象变为了局部对象
  * 原因： 为了在jquery代码块更快的访问window对象
  ```
    (function(a, b){ })(window)
  ```
### jquery对象
* 类数组对象

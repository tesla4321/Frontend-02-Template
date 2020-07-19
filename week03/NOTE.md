学习笔记

### 这周主要讲的JavaScript的代码结构，运行时和事件循环相关的内容。

#### 运表达式

Member，New，Call运算优先级依次递减。JavaScript表达式运算的时候会带有类型转换。类型转换通过一定的规则来让比较或者进行运算的值转换为相同的类型。当Object参与转换和运算的时候会产生装箱和拆箱操作。Object的内部实现（toString,valueOf,Symbol.toPrimitive）决定了转换的结果。

#### 语句

completion record以及各种statement，声明，预处理，作用域，这一部分主要是理论性地讲解JavaScript的代码结构。

#### 结构化

* 宏任务，微任务，函数调用

JavaScript 引擎执行JavaScript代码的过程->事件循环->获取代码，执行代码，等待任务。

JavaScript 函数调用栈->Environment Record ->把导入（被调用）的模块所包含的变量（常量）带到调用的函数中。





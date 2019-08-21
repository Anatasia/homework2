# homework2
# homework2
## 1.Why should you have minimum scope for variables?
#### 控制变量作用域，降低出错的可能性；增强代码的可读性和可维护性。
## 2.Why should you understand performance of String Concatenation?
#### 1）字符串连接很常见，如果处理不当，会导致严重的性能问题；
#### 2）+,String.concat(),StringBuffer,StringBuilder几种不同字符串的拼接方式在不同使用场景下性能存在差异，可根据实际情况选择合适的字符串拼接方式;
## 3.What are the best practices with Exception Handling?
#### 1）异常包装；
#### 2）出现异常时，系统能正常运行；
#### 3）最先捕获特定的异常；
## 4. When is it recommended to prefer Unchecked Exceptions?
#### unchecked exceptions被用来发出和程序逻辑以及一些正在进行的假设相关的错误情况（如非法参数，空指针，不支持的操作等等）;
## 5.When do you use a Marker Interface?
#### 1）标识接口是没有任何方法和属性的接口。标识接口不对实现它的类有任何语义上的要求，它仅仅表明实现它的类属于一个特定的类型；
#### 2）比如java.io.Serializable和java.rmi.Remote等接口便是标识接口；
#### 3）当需要表明类属于某个类型时，可以使用标识接口。
## 6.Why are ENUMS important for Readable Code? 
#### 1）枚举是类型安全的，不会出现取值范围错误的问题；
#### 2）客户端不需要建立对枚举中常量值的了解，使用起来很方便，并且可以容易地对枚举进行修改，而无需修改客户端；
#### 3）如果常量从枚举中被删除了，那么客户端将会失败并且将会收到一个错误消息。枚举中的常量名称可以被打印，因此可以获取更多信息。
## 7.What is functional progtamming?
#### 1）函数式编程中没有赋值语句，因此变量一旦有了值就不会再改变；
#### 2）没有能够改变表达式值的副作用，可以在任何时候对它求值；
#### 3）由于能够在任何时候对表达式求职，所以可以用变量的值来自由替换表达式，反之亦然——即程序是“引用透明”的。
## 8.Why should you prefer Builder Pattern to build complex objects?
#### 1）Builder Pattern 可以将一个复杂对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示;
## 9.Why should you avoid floats for Calculations?
#### 1）floats本身是不准确的，因为计算器是二进制的，浮点数无法用二进制精确表示，因此在计算时避免使用floats。
## 10.Why should you build the riskiest high priority features first?
####  1）避免遗漏

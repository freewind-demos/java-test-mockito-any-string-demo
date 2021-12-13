Java Test Mockito AnyString Demo
=====================

当我们给mockito设置行为时，可以使用`anyString`告诉我们在某种条件下，不关心具体传入的值。

这种情况比设置一个`null`要更加表意

注意：`anyString`是一个matcher，只用来验证。传参数时应该构造一个正常的string

```
mvn test
```
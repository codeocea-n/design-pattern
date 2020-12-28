# 设计模式



## 六大设计原则

1. 单一职责原则

   There should never be more than one reason for a class to change.

   一个接口或类只有一个原因引起变化，也就是一个接口或类只有一个职责 

2. 里氏替换原则

   Functions that use pointers or references to base classes must be able to use
   objects of derived classes without knowing it.
   
   所有引用基类的地方必须能透明地使用其子类的对象。
   
   通俗点讲，只要父类能出现的地方子类就可以出现，而且替换为子类也不会产生任何错误或异常，使用者可能根本就不需要知道是父类还是子类

3. 依赖倒置原则

   High level modules should not depend upon low level modules. Both should depend upon
   abstractions. Abstractions should not depend upon details. Details should depend upon abstractions.

   高层模块不应该依赖低层模块，两者都应该依赖其抽象

   抽象不应该依赖细节

   细节应该依赖抽象

4. 接口隔离原则

   The dependency of one class to another one should depend on the smallest possible interface.

   类间的依赖关系应该建立在最小的接口上。要求接口的方法尽量少

5. 迪米特法则

   一个对象应该对其他对象有最少的了解。通俗地讲，一个类应该对自己需要耦合或调用的类知道得最少，你（被耦合或调用的类）的内部是如何复杂都和我没关系，那是你的事情，我就知道你提供的这么多public
   方法，我就调用这么多，其他的我一概不关心。

6. 开闭原则

   Software entities like classes,modules and functions should be open for extension but closed for
   modifications.

   一个软件实体如类、模块和函数应该对扩展开放，对修改关闭。
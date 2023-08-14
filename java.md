# java se
## java intro
### java语言特点
- 面向对象，封装继承多态
- 支持多线程
- 异常处理和自动内存管理机制
### JVM、JDK、JRE
- JVM：java虚拟机是运行java字节码的，JVM根据不同的系统有不同的实现。目的是同样的字节码 即.class文件，JVM会给出相同的机器码。从.class——>机器码这一步，会根据代码是否是热点代码，不是热点代码则通过解释器逐行解释执行，是热点代码则通过JIT编译器，just-in-time compilation。当JIT完成第一次编译后，其会将字节码对应的机器码保存下来，下次直接使用。
- JRE：java runtime environment，是java运行时环境，包括JVM和java class library。
- JDK：java development kit，是提供给开发者使用的java sdk，除了JRE之外还包含将java源码即.java文件编译为字节码的编译器javac，以及jdb调试器，jconsole可视化监控工具等等
### 为什么说java语言编译与解释共存？
因为java程序先经过javac编译器编译，生成.class字节码文件，这种字节码必须由java解释器来解释执行。
### java与c++的区别
-java不提供指针直接访问内存，程序内存更加安全
-java有自动的内存管理垃圾回收机制，不需要手动释放无用内存
-java只有单继承，但可以实现接口的多继承
## java language basics
### Variable

# 1、Java中的序列化和反序列化是什么
（1）**序列化**是将对象转换为字节流的过程，这样对象可以通过网络传输、持久化存储或者缓存。Java提供了java.io.Serizlizable接口来支持序列化，只要类实现了这个接口，就可以对该类的对象进行序列化。
（2）**反序列化**是将字节流重新转换为对象的过程，即从存储中读取数据并重新创建对象。

# 2、什么是Java中的不可变类？
不可变类是指在创建后其状态（对象的字段）无法被修改的类。一旦对象被创建，它的所有属性都不能被更改。这种类的实例在整个生命周期内保持不变

# 3、Java中Exception和Error有什么区别
Excepdtion和Error都是Throwable类的子类（在Java中代码只有继承了Throwable类的实例才可以被throw或者被catch），它们表示在程序运行时发生的异常或错误情况；其中，Exception表示可以被处理的程序异常，Error表示系统级的不可恢复情况（JVM层次内系统级的、无法预料的错误，程序无法通过代码进行处理或恢复）。

# 4、Java的优势
（1）跨平台（可移植性，通过jvm实现）——即一次编写，处处运行
（2）垃圾回收——自动回收库存，提高内存管理效率
（3）相关生态——强大的类库和第三方组件
（4）面向对象——封装、继承和多态

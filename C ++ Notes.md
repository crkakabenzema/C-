# C ++ Notes:

## namespace:

命名空间：实际上就是一个由程序设计者命名的内存区域，程序设计者可以根据需要指定一些有名字的空间域，把一些全局实体分别放在各个命名空间中，从而与其他全局实体分隔开来

如： namespace ns1 //指定命名中间nsl 
      { int a； 
      double b; } 

现在命名空间成员包括变量a和b，注意a和b仍然是全局变量，仅仅是把它们隐藏在指定的命名空间中而已。如果在程序中要使用变量a和b，必须加上命名空间名和作用域分辨符“::”，如nsl::a，nsl::b



## <<:

<< 为运算符重载



## ::

:: 为访问修饰符



## g++应用说明：

```cmd
$ g++ helloworld.cpp -o helloworld
```

使用 -o 选项，生成指定可执行程序的文件名helloworld

执行 helloworld:

```cmd
$ ./helloworld
Hello, world!
```

如果是多个 C++ 代码文件，如 runoob1.cpp、runoob2.cpp，编译命令如下：

```cmd
$ g++ runoob1.cpp runoob2.cpp -o runoob
```



## 注释：

- // - 一般用于单行注释。
- /* ... */ - 一般用于多行注释。



## 内置类型：

| 布尔型   | bool    |
| -------- | ------- |
| 字符型   | char    |
| 整型     | int     |
| 浮点型   | float   |
| 双浮点型 | double  |
| 无类型   | void    |
| 宽字符型 | wchar_t |



## typedef 声明：

如：

```cmd
typedef int feet;   //feet 是 int 的另一个名称
```


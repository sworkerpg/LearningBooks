# Hello World

## Hello World源码

```
#include <stdio.h>

int main()
{
    printf("Hello world\n");
    return 0;
}
```

* main函数是程序的入口，由操作系统发起程序的调用
* return 0 返回0代表成功，返回-1代表运行失败
* 一个程序中有且只有一个main函数
* printf 格式打印（print打印，f-format）

## 从源文件到可执行文件的步骤

* 预处理 -&gt; 编译 -&gt; 汇编 -&gt; 链接

### 以vim为编辑器，gcc为编译器为例

> 1. vim hello.c
> 2. gcc -E hello.c -o hello.i   //处理文件包含，宏和注释
> 3. gcc -S hello.i  -o hello.s  //编译为汇编文件
> 4. gcc -c hello.s -o hello.o  //经汇编后为二进制的机器指令
> 5. gcc     hello.o -o hello     //链接所有用的库，生成可执行文件

## 注释的问题
* // 代表单行注释
* /**/ 代表多行注释，但是该注释不支持嵌套
* 采用 if 0  endif 的方式来进行多行注释




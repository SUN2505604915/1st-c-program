# 1st-c-program

第一次的项目

`README.md` 是Markdown文件

[这里是Markdown的教程](https://www.runoob.com/markdown/md-tutorial.html)

``` C
#include<stdio.h>
int main()
{
  int a[3][4];
  printf("hello world");
  printf("Welcome to C Programming\n");
  return 0;
}  
```

`“void main()”`的用法并不是任何标准制定的。

C語言标准語法是`“int main()”`，任何实现都必须支持`int main(void) { /* ... */ }`和`int main(int argc, char* argv[]) { /* ... */ } ` 

[来源](http://www.stroustrup.com/bs_faq2.html#void-main)

## 环境

Ubuntu  18.04

## 代码讲解

后续待更新...

## 使用方法

lm是已经生成可执行的exe文件

代码从test.in中读入，生成四元式输出到test.out中



### 编译方法

1. lex.l     词法分析器
2. yacc.y  语法分析器
3. xu.h     头文件

只需要以上三个文件即可，其他文件均为生成的中间文件



使用以下命令进行编译即可

```
bash gen.txt
```


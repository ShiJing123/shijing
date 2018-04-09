# shijing
python 3.7
1.用缩进表示代码块
if True:
     print true
else:
     print false
2.数据类型：整形，布尔，浮点数，复数。
    int (整数), 如 1, 只有一种整数类型 int，表示为长整型，没有 python2 中的 Long。
    bool (布尔), 如 True。
    float (浮点数), 如 1.23、3E-2
    complex (复数), 如 1 + 2j、 1.1 + 2.2j
3.字符串：
  python中“”和‘’是一样的
  按照字面意思级联字符串
  字符串连接用+，用*表示重复
  字符串有两种索引方式，从左向右以0开始，从右向左以-1开始。
  str='nobbya'
  print(str)
  print(str[0:-1]) 输出从第一个到倒数第二个的字符
  print(str*2) 输出字符串两次
  print(str+'你好')  连接字符串
4.空行也是代码的一部分
5.接受用户输入 input()  按下回车后等待用户输入
6.多个语句构成代码组
缩进相同的代码构成一个代码块，if,while,case等都是使用相同缩进构成代码块，首行以关键字开始，以冒号结束，之后的代码块构成子代码。
 if a:
    good
 elif b:
    liang
 else:
   jige
7.print输出
默认的print输出是换行的，不换行要在末尾加end=“ ”
换行
print(x)
print(y)
不换行
print(x,end=" ")
print(y,end=" ")
8.import和from...import...
9.help()函数
调用help()函数，可以获得某个函数的文档 eg（help(max)）






# 编译原理第二次作业

## 焦培淇  PB17151767

---
## 2.1 （e）
&emsp;不知道

## 2.2
| 词法单元 | 记号 | 属性值 |
| --- | --- | --- |
| long | long | 无 |
| gcd | id | 指向符号表的gcd项的指针 |
| ( | 标点符号 | 左括号 |
| long | long | 无 |
| p | id | 指向符号表的p项的指针 |
| ,  | 标点符号 |  逗号  |
| q  | id |  指向符号表q项的指针  |
| )  | 标点符号 |  右括号  |
| {  | 标点符号 |  左大括号  |
| if  | if | 无 |
| %  | 操作符 |  取余  |
| ==  | relation |  判断相等  |
| 0  | number |  数值0  |
| return  | return | 无 |
| ;  | 标点符号 |  分号  |
| else  | else | 无 |
| }  | 标点符号 |  右大括号  |

## 2.3 （e）
表示含有偶数个0和偶数个1的01串。

## 2.4 （a）
&epsilon;\*(A|a)&epsilon;\*(E|e)&epsilon;\*(I|i)&epsilon;\*(O|o)&epsilon;\*(U|u)&epsilon;\*

## 2.4 （f）
(00|11)\*((01|10)(00|11)\*(01|10)(00|11)\*)\*

## 2.4 （i）
b\*(abb*)\*(a|&epsilon;)

## 2.7 （c）
![图1](https://github.com/jpq6699/hellloworld/blob/master/2.7c.jpg?raw=true)

状态转换序列为1->2->5->6->7->8->9->10->2->5->6->7->8->9
->8->9->10->2->5->6->7->8->9->10->11
## 2.11 
第一个正规式的NFA如图一所示

![图1](https://github.com/jpq6699/hellloworld/blob/master/2.11(1).jpg?raw=true)

第二个正规式的NFA如图二所示

![图2](https://github.com/jpq6699/hellloworld/blob/master/2.11(2).jpg?raw=true)

第三个正规式的NFA如图三所示

![图1](https://github.com/jpq6699/hellloworld/blob/master/2.7c.jpg?raw=true)

三个NFA均可转化为如下所示的DFA,因此其他们是等价的。

![图1](https://github.com/jpq6699/hellloworld/blob/master/2.11(4).PNG?raw=true)

##2.15
![图1](https://github.com/jpq6699/hellloworld/blob/master/2.15.jpg?raw=true)

其中E为接受状态。
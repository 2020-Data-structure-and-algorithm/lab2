# Lab 2

## 教学团队
### 教师：郑骁庆
联系方式：[zhengxq@fudan.edu.cn](http://zhengxq@fudan.edu.cn)
### 助教：
- 陈雷远 [20210240034@fudan.edu.cn](http://20210240034@fudan.edu.cn) 
- 徐健涵 [20210240021@fudan.edu.cn](http://20210240021@fudan.edu.cn) 


## 任务

- 最小栈

- 用队列实现栈

> 本节目标：
>
> 1. 掌握栈的简单实现，并在基础上增加了一个查找最小数值的功能
> 2. 掌握队列与栈之间的关系，能够使用队列来构造栈

## 获取及提交lab

**获取**：通过 `https://github.com/2020-Data-structure-and-algorithm/lab2`，获取。

**提交**：将提交物放到自己lab2的文件夹中，将文件夹压缩，压缩文件名应为你的 `学号_姓名` （如`20210240034_陈雷远`），提交至 `FTP` 站点（`ftp://10.12.5.33`）本课程文件夹的`work_upload/lab2` 文件夹下。

**提交物**：本课程要求使用java或python语言完成，本次lab如果用java语言完成需提交MinStack.java 以及 MyStack.java；python语言需提交MinStack.py 以及 MyStack.py。

**截止时间**：2020年9月30日 23：59：59

## 1.设计最小栈
### 问题描述
设计一个支持 ```push``` ，```pop``` ，```top``` 操作，并能在常数时间内检索到最小元素的栈。


### 示例：
```
输入：
["MinStack","push","push","push","getMin","pop","top","getMin"]
[[],[-2],[0],[-3],[],[],[],[]]

输出：
[null,null,null,null,-3,null,0,-2]

解释：
MinStack minStack = new MinStack();
minStack.push(-2);
minStack.push(0);
minStack.push(-3);
minStack.getMin();   --> 返回 -3.
minStack.pop();
minStack.top();      --> 返回 0.
minStack.getMin();   --> 返回 -2.
 ```

### 提示：

所有操作值都在 [1, 100] 之内。
操作次数将在  [1, 1000] 之内。

## 2.用队列实现栈
### 问题描述
使用库中的队列实现栈的下列操作：

push(x) -- 元素 x 入栈
pop() -- 移除栈顶元素
top() -- 获取栈顶元素
empty() -- 返回栈是否为空

### 注意：
你只能使用队列的基本操作-- 也就是 ```push to back```, ```peek/pop from front```, ```size```, 和 ```is empty``` 这些操作是合法的。
你可以假设所有操作都是有效的（例如, 对一个空的栈不会调用 ```pop``` 或者 ```top``` 操作）。
# How to simply use the markdown editor

## 网络链接

​	***Welcome to***  [My website](https://zicongxie.com)  ***to browse some blogs that I have written.***

​	使用以下两种格式：

	* \[链接名称](链接地址)
	* <链接地址>

## 代码块

```c++
#include<iostream>
using namespace std;
int main(void)
{
    cout<<"Hello World!!!"<<endl;
    return 0;
// 使用代码块方法：```使用三个反引号包起来 ```  
```

## 表格

使用 | 作为列表列的分隔符，使用---作为行的分隔符

| 姓名 |   学号    | 成绩 |
| :--: | :-------: | :--: |
| 小红 | 201824101 | 456  |
| 小明 | 201824102 | 701  |
| 小刚 | 201824103 | 636  |

## 列表

* :smile: :joy: :angry: :e-mail:  emoij 使用：后跟英文字母
* 1. 嵌套列表  使用：*或者1.后加空格
  2. Hello
  3. emememmmm
  4. hahaha  

## 区块

> 区块引用方法：段落开始处加>符号
>
> >
> >
> >**嵌套区块**

## 图片

>！[alt 属性文本] (图片地址)
>
>！[alt 属性文本] (图片地址 " 可选标题")

![小黄鸭](C:\Users\xiezi\Desktop\temp\下载.jpg)

![帅不帅](C:\Users\xiezi\Pictures\Camera Roll\QQ图片20190525130858.jpg)

## 段落字体格式

1. 斜体：一个*包起来

2. 粗体：两个*包起来

3. 粗斜体：三个*包起来

4. 分割线：三个以上*或者-或者_可加空格来对空行加分割线

5. -----

6. 删除线：两端用~~包起来~~

7. 下划线：使用HTML的<u><u>标签</u>

8. 脚注：  [^markdown] 

[^markdown]: A wonderful and simple text editor.
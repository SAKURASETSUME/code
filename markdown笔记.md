# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题



**段落直接用回车分割即可 不要用tab或空格缩进** 

**换行直接结尾敲两个空格之后回车即可 或者用html的br标签也可以实现换行**

**粗体可以用四个星号来实现  或者用四个下划线（并不推荐）**<br>__test__<br>*斜体使用两个星号或两个下划线就可以实现*<br>***显而易见 粗斜体就是六个星号了***



> 引用使用">"符号<br>引用可以包含多个段落
>
> - 引用可以包含其他markdown格式元素**example**
>
> >引用可以嵌套 只需要在引用里面再进行一次引用就可以



**有序列表直接输入数字加英文句点即可**

1. a
2. b



**无序列表可以在前面加破折号 星号或加号 例如:**

- test
- test2

**列表是可以嵌套其它元素的 输入回车就可以实现 比如**

- fist item

  > second item

- third item



**代码块 只需要用三个反引号*```*加上要写的语言类型即可**

```c
#include<stdio.h>
int main(){
    printf("hello world!");
    return 0;
}
```



**如果要将短语或单词表现为代码 用一个反引号包裹就可以**

`int`

**有序列表和无序列表是可以嵌套的**

1. a
2. b
3. c
   - a
   - b
4. aa
5. b



**创建分割线 单独起一行用三个星号 破折号或者下划线**

***

***test***

___

**超链接**<br>对应语法代码:[超链接显示名](url "title")<br>example:

[存档仓库](https://github.com/SAKURASETSUME/galgame "galgame")<br>

如果是简单的引用url 直接用尖括号括起来:**<https://github.com/SAKURASETSUME/galgame>**



**图片语法**

![图片alt](路径 "title")

**在图片中添加跳转链接 只需要用方括号括起来图片 之后用圆括号加上链接即可**

[![图片alt]](路径 "tiele")(https://github.com/SAKURASETSUME/galgame)



显示markdown语法内容 直接在语法前面加入反斜杠即可

\**a**



**markdown会对特殊字符自动转译 &要写成\&amp;  <要写成 \&lt;	**












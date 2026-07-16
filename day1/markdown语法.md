# 这是一个一级标题

## 二级标题
**加粗ing四个*** 简单文本信息

  “  ”换行

  换段==回车*2==

*这是一个斜体文字*

***这是一个加粗的斜体***

~~**删除线**~~

***
分割线

- 这是一个无序列表
  
* 我是另一个无序列表

+ 我是另另一个无序列表

6. 有序列表
2. 中间有空格
3. 按顺序进行

5. 自定义数字
    - 二级列表前加tab
      - 三级列表
        - 四级列表  
6. 从第一级开始
    5. 二级数字列表
       1. 这好像不是一个三级列表 
        项内换行 

接着往后写

* [ ] 这是一个勾选框
* [x] 再来一个
* [ ] 一个* [ ] 英文空格
* [ ] 打勾[x]中间加一个x

***
```cpp
//这是一个c++代码块
#include<iostream>
using namespace std;
int main()
{
    cout<<"helloworld"; 
    return 0;
}
```
只有个行内`代码块，两个`` `

> 应用一段部分
> 一个大于号

> 中间加一个回车分成两块
> ```cpp
> #inclde<iostream>
> using nemespace std;
> int mian()
> {
>  //嵌套一个代码块
>  //每一行前面加一个>
> }
> 
> ```

> vvxc
> fsd 
> ```cpp
> dfs fd 
> ```

着是一个github的超链接[github](https://github.com)//这个好像不能嵌套？！
==中括号写名字，小括号写地址==着也是一个[github][g]连接使用标签写法。


添加了一个脚注[^1]
第二个脚注[^2]，中括号内包^



==**紧急插入一个**[markdowncheatsheet](https://www.markdownguide.org/cheat-sheet/)==

[g]: https//github.com

[^1]:这是一个脚注，只能用英文冒号
[^2]:脚注二


再插入一个图片
![图片](https://gips0.baidu.com/it/u=1690853528,2506870245&fm=3028&app=3028&f=JPEG&fmt=auto?w=1024&h=1024)
==!后同链接插入==


| 年龄 | 姓名 | 性别 |
| :----: | ---- | - |
|张三|18| 男|
|李四|19| 男 |
|发士大夫大师傅发射点法大师傅|12|2|


<img src =" https://gips0.baidu.com/it/u=1690853528,2506870245&fm=3028&app=3028&f=JPEG&fmt=auto?w=1024&h=1024" width = 50px height = 200px></img>



<span style = "color: red ;font-size : 21px">html的语法也支持
</span>


这是一个上标表示 x^2^  ==用两个^^包裹起来==
这是一个下标 x~2~ ==用两个~~包裹起来==

这是一个数学公式$$ x^2=y+
\frac{1}{10}z+\sqrt{(4+x)+5}$$ 
好像不支持嵌套在`这个`里面
##MarkDown 语法

标题：

#标题1
##标题2 
###标题3
####标题4
#####标题5
######标题6

斜体与加粗：

*斜体* 
**加粗**

键盘按键：

<kbd>ctrl</kbd>

列表：

- 第一行
- 第二行
- 第三行
    + 次一行
    + 次二行
    + 次三行
        * 次次一行
        * 次次二行
        * 次次三行

图片：

<kbd>win shift k</kbd> ==![图片]()

链接：

<kbd>win ctrl v</kbd> == [链接]()  

插入代码：

``` java
public Demo{
    public static void main(String args[]){
        println("hello world")
    }
}
```

``` c
int main(){
    printf("hello world")
}
```

数学公式：

$x^{y^z}=(1+{\rm e}^x)^{-2xy^w}$ 

表格：

| 一列 | 二列 |三列  |
| - |||
| 一行 | 一行 | 一行 |
| 二行 | 二行 | 二行 |

分割线：

***
注：*在OmniMarkupPreviewer.settings*
```
{

 "mathjax_enabled": true,
 
}
```
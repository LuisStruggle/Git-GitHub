# 一级标题

## 二级标题

### 三级标题

> 提示：这种写法共有六级标题

---

	单行或多行文本，即每行开头都加一个Tab

---

1. 有序列表（注意空格），元素1
	1. 有序列表（注意空格），元素2
	1. 有序列表（注意空格），元素3

---

* 无序列表（注意空格），元素1
	* 无序列表（注意空格），元素2
	* 无序列表（注意空格），元素3

---

**锚点的使用**

* [点击跳转](#jump)

---

**文本强调**

*斜体文本*

~~删除文本~~

---

> 块级元素

区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

---

[我是链接](https://github.com/LuisStruggle "悬停显示")

![alt 插入图片](test.jpg)

<https://github.com/LuisStruggle>（这个写法markdown会自动转为a标签的形式）

<18300767078@163.com>（电子邮箱地址）

---

\*转译符反斜杠的用法\*

**下面是代码区块的各种写法**

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

---

## jump

---

**代码高亮**

```Java
public static void main(String[]args){} //Java
```

**复选框**

* [x] 需求分析
* [x] 系统设计
* [x] 详细设计
* [ ] 编码
* [ ] 测试
* [ ] 交付

**表格**

|第一列|第二列|
|-----|-----|
|字段一|字段二|

**表格可以指定对齐方式**

|左对齐|居中|右对齐|
|:----|:--:|----:|
|col  |some| $1600|
|col  |cent|   $12|
|zeb  |are |    $1|

**图片链接**

[![alt 插入图片][logo]][url]

[url]:https://github.com/LuisStruggle "我的主页"
[logo]:test.jpg "点击图片进入我的主页"
Markdown 的学习	
Markdown的出现是为了方便编写人员易写易读
在其中可以加入HTML标签，但是在HTML标签中添加Markdown格式的语法将不会被处理

#### HTML标签
<table>
	<tr>
		<td>HTML标签</td>
	</tr>
</table>
<div>HTML区块标签中书写Markdown语法</div>

<div>*着重*</div>
<span>*着重*</span>

mk:
```markdown
<div>*着重*</div>

<span>*着重*</span>
```


#### 高阶标题

最高阶标题
==========

mk:
```
最高阶标题
==========
```

第二阶标题
----------

```
第二阶标题
----------

```

# H1标题
## H2标题 
###### H6标题

mk:
```markdown
# H1标题
## H2标题 
###### H6标题

```

#### 引用标签

> this is a blockquotes label

mk:
```markdown
> this is a blockquotes label
```

> # 区块嵌套标题H1

mk:
```markdown
 > # 区块嵌套标题H1
```

#### 代码块
```js
	var str = require('express');
```

```html
	<div>这个html代码块</div>
```

```css
	.body{
		margin:0;
		padding:0;
	}
```

#### 列表
* 无序列表

+ 无序列表

- 无序列表

mk:
```markdown
* 无序列表

+ 无序列表

- 无序列表
```


1. 有序列表
2. 有序列表

mk:
```markdown
1. 有序列表
2. 有序列表
```

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.   
	Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,  
    viverra nec, fringilla in, laoreet vitae, risus.
	*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.    
	Suspendisse id sem consectetuer libero luctus adipiscing.

mk:
```markdown
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.   
	Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,  
    viverra nec, fringilla in, laoreet vitae, risus.
	*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.    
	Suspendisse id sem consectetuer libero luctus adipiscing.
```

	> this is a blockquotes


#### 分割线
*** 

mk:
```markdown
***
```

#### a链接

this is [a example](http://www.alltuu.com) inline link
this is [Google][] inline link
[Google]:http://google.com
this is [a example](http://www.alltuu.com '喔图摄影') inline link include title attribute

mk:
```markdown
this is [a example](http://www.alltuu.com) inline link
this is [Google][] inline link
[Google]:http://google.com
this is [a example](http://www.alltuu.com '喔图摄影') inline link include title attribute

```

*single asterisks*
_single asterisks_

**single asterisks**
__single asterisks__

```markdown
*single asterisks*
_single asterisks_

**single asterisks**
__single asterisks__
```

java use the `println` function input

```markdown
java use the `println` function input
```

在一段话中添加反引号 `` ` ``
在一段话中添加反引号 \`

####图片插入

![来自喔图摄影--摄影师；苑小许](http://pub.alltuu.com/face/PG36071/latest.jpg@1e_65w_65h_1c_0i_1o_90Q_1x "摄影师；苑小许")

mk:
```	markdown
![来自喔图摄影--摄影师；苑小许](http://pub.alltuu.com/face/PG36071/latest.jpg@1e_65w_65h_1c_0i_1o_90Q_1x "摄影师；苑小许")
```

#### 复选框

- [ ] Screen width (integer)
- [x] Service worker support
- [x] Fetch support
- [ ] CSS flexbox support
- [ ] Custom elements

mk:
```markdown
- [ ] Screen width (integer)
- [x] Service worker support
- [x] Fetch support
- [ ] CSS flexbox support
- [ ] Custom elements

```

#### 表格

| table |   are |    cool     |
|-------|:-----:|------------:|
| col   | aret test1234125123 | coolqweqwer |
| col   | are test xxxxxxxxx | cooltest |
| col   | are testcccccc| cooltest1234567890 |
| col   | are test0000000000000000 | cooltestxxxxxxx |

mk:
```markdown
| table |   are |    cool     |
|-------|:-----:|------------:|
| col   | aret test1234125123 | coolqweqwer |
| col   | are test xxxxxxxxx | cooltest |
| col   | are testcccccc| cooltest1234567890 |
| col   | are test0000000000000000 | cooltestxxxxxxx |

```












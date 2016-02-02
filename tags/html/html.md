html标签

##### 介绍

此元素可告知浏览器其自身是一个 HTML 文档。
`<html>` 与 `</html>` 标签限定了文档的开始点和结束点，在它们之间是文档的头部和主体。正如您所了解的那样，文档的头部由 [`<head>`](../head/head.md) 标签定义，而主体由 [`<body>`](../body/body.md) 标签定义。

##### 实例 

```html
<html>
	<head>
	  这里是文档的头部 ... ...
	</head>
	<body>
	  这里是文档的主体 ... ...
	</body>
</html>
```

##### 效果 

请复制代码自行在浏览器中查看效果！

##### 属性


|  属性   |   值   |   描述  |
|--------|--------|--------|
|manifest|url|定义一个 URL，在这个 URL 上描述了文档的缓存信息。|
|[xmlns](http://www.w3school.com.cn/tags/tag_prop_xmlns.asp)|http://www.w3.org/1999/xhtml|定义 XML namespace 属性。|

##### 注意

注释：即使 html 元素是文档的根元素，它也不包含 doctype 元素。doctype 元素必须位于 html 元素之前。

[<< 返回列表](../index.md)
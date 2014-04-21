本课总结
==========

本课主要回顾了HTML语义化的一些知识，强调了HTML的文档结构，在不考虑布局的情况下如何保持HTML的结构清晰。

在写HTML的时候，避免出现在有明确语义含义的情况下使用`<div>,<span>`这类无明确含义的标签

一些关于HTML语义化的文章：

*[语义化你的HTML标签和属性](http://www.blueidea.com/tech/site/2006/3771.asp)
*[HTML标签的语义化概念、意义和实践](http://www.5icool.org/a/201006/537.html)
*[语义化的HTML结构到底有什么好处？](http://www.css88.com/archives/1668)
*[再谈语义化](http://ued.ctrip.com/blog/?p=2735)

做本科作业时出现的一些以前不清楚的东西的总结：

1.`<html lang="en">`中`lang='en'`表示使用的语言是英文，`lang='zh'`表示使用中文，基本没什么大用处，对一些xml/xhtml还是有作用的

2.HTML5模板生成的head里的一些语句的作用

`<link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />`网站地址前个性显示网站图标

注意点：
一般ICON的分辨率是16*16，大小1-2k，建议不宜过大
href也可以是绝对路径或URL 比如：href="/favicon.ico"href="http://www.xxx.com/favicon.ico"
当favicon.ico被置于文档根目录时，将会被一些不处理link元件的浏览器找到，即使站点上没有指向它的链接
把图标命名为favicon.ico 一般不用写link就可以应用于站点下的每一个页面文件
favicon.ico不是必须要放在根目录，名称也可以自己定义，只是在link中具体的href对应好即可

PS：如果用IE仍然不显示小图标，问题很可能出在缓存的历史记录上。 
请选择选择Internet选项，删除浏览历史记录，重新刷新页面一般即可解决。

这里有 [apple-touch-icon,shortcut icon和icon的区别](http://wayne173.iteye.com/blog/940524)


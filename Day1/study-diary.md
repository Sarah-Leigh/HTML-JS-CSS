# 标签

1. __<div>__标签会另起一行
   __<span>__标签不会换行，内容有多宽就占用的多宽

2. __<meta>__标签用来规定html的元数据，这些信息不会显示在页面上，常用的属性有：

   * content：当有http-equiv或name属性时必须有它，它是对http-equiv或name的补充说明

   * http-equiv：添加http头部的内容

   * name：供浏览器进行解析，只有浏览器能解析你传入的name时才是有意义的，常用于浏览器兼容问题

     例如<meta name="renderer”, content="webkit"> 是告诉浏览器用webkit内核来进行解析
   * charset：解决乱码问题，一定要写到第一行 <meta charset="utf-8">

3. __<link>__标签用来引用外部资源的样式应用到本html文档，通过rel来赋值，href来记录url
   例如：<link ref="stylesheet" type="text/css href="*.css">、<link ref="icon”, href="/favicon.ico">

4. __<kbd>__标签表示值是从键盘输入的

# 属性

1. __data-*__：自定义数据，可应用在任意标签内，自定义的数据能被js利用，属性名不能有大写字母
语法：<element data-*=”somevalue”>

# CSS

1. font-family：字体，常见的是sans-serif，表示无衬线字体，是一种通用字族，它能保证字一定可以正常显示
2. display：规定了元素的显示类型，常见的有以下几种：

   * none：不显示
   * block：块级元素，前后带换行符
   * inline：内联元素，前后不带换行符
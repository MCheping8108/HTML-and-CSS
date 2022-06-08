# 第一次学的HTML和CSS
自从学了python很久，我感觉python不太新鲜的感觉了
所以！我第一次写的HTML和CSS

**先来看效果图**
![输入图片描述](README_md_files/b7ce14c0-d7ed-11ec-9e02-a9ad101d2258.jpeg?v=1&type=image)

~~（别问我最下面的东西是什么）~~
# HTML介绍
HTML的全称为[超文本标记语言](https://baike.baidu.com/item/%E8%B6%85%E6%96%87%E6%9C%AC%E6%A0%87%E8%AE%B0%E8%AF%AD%E8%A8%80/6972570)，是一种[标记语言](https://baike.baidu.com/item/%E6%A0%87%E8%AE%B0%E8%AF%AD%E8%A8%80/5964436)。它包括一系列[标签](https://baike.baidu.com/item/%E6%A0%87%E7%AD%BE/2440469)．通过这些标签可以将网络上的[文档](https://baike.baidu.com/item/%E6%96%87%E6%A1%A3/1009768)格式统一，使分散的[Internet](https://baike.baidu.com/item/Internet/272794)资源连接为一个逻辑整体。HTML文本是由HTML命令组成的描述性[文本](https://baike.baidu.com/item/%E6%96%87%E6%9C%AC/5443630)，HTML命令可以说明[文字](https://baike.baidu.com/item/%E6%96%87%E5%AD%97/612910)，[图形](https://baike.baidu.com/item/%E5%9B%BE%E5%BD%A2/773307)、[动画](https://baike.baidu.com/item/%E5%8A%A8%E7%94%BB/206564)、[声音](https://baike.baidu.com/item/%E5%A3%B0%E9%9F%B3/33686)、[表格](https://baike.baidu.com/item/%E8%A1%A8%E6%A0%BC/3371820)、[链接](https://baike.baidu.com/item/%E9%93%BE%E6%8E%A5/2665501)等。 [1]

[超文本](https://baike.baidu.com/item/%E8%B6%85%E6%96%87%E6%9C%AC/2832422)是一种组织信息的[方式](https://baike.baidu.com/item/%E6%96%B9%E5%BC%8F/3616191)，它通过[超级链接](https://baike.baidu.com/item/%E8%B6%85%E7%BA%A7%E9%93%BE%E6%8E%A5/313121)方法将文本中的文字、图表与其他[信息媒体](https://baike.baidu.com/item/%E4%BF%A1%E6%81%AF%E5%AA%92%E4%BD%93/8400627)相关联。这些相互关联的信息媒体可能在同一文本中，也可能是其他文件，或是[地理位置](https://baike.baidu.com/item/%E5%9C%B0%E7%90%86%E4%BD%8D%E7%BD%AE/797988)相距遥远的某台[计算机](https://baike.baidu.com/item/%E8%AE%A1%E7%AE%97%E6%9C%BA/140338)上的文件。这种组织信息方式将分布在不同位置的信息资源用随机方式进行连接，为人们查找，[检索](https://baike.baidu.com/item/%E6%A3%80%E7%B4%A2/11003896)信息提供方便。
## 代码展示

	<html lang="en-US" or "en">
这个代码是设置这个文档语言，你每一次在编辑器中创建一个html文件它这个语言默认设置英语。那具体有什么作用（看效果图）

![输入图片描述](README_md_files/7beedcd0-d7ef-11ec-9e02-a9ad101d2258.jpeg?v=1&type=image)

看到了吧？
因为这个文档语言被设置成**英语**了，所以浏览器（任意浏览器）都会被识别成 “这是一个html英语文档” ，然后就会弹出来这个翻译器（图片）

（有人真的不会把文档语言设置成英语吧）


	<head>
		<meta charset="UTF-8">
	</head>
这个代码是字符编译，用来解析字体，而且 “UTF-8” 是全世界通用的字符编码

有人肯定会问：你写上这个干什么？

答：如果我不写这个的话。。。

![输入图片描述](README_md_files/10dcd1c0-d7f1-11ec-9e02-a9ad101d2258.jpeg?v=1&type=image)
（观看者：这是什么~~狗屁~~玩意？！我都看不懂的好吧！！！）
所以，你懂的

	<head>  
	  <!--字符编码-->  
	  <meta charset="UTF-8">  
	  <!--处理兼容IE-->  
	  <meta http-equiv="X-UA-Compatible" content="IE=edge">  
	 <meta name="viewport" content="width=device-width, initial-scale=1.0">  
	  <!--页面标题-->  
	  <title>Hello World!</title>  
	  <!--引用CSS-->  
	  <link rel="stylesheet" href="./css/index.css">  
	</head>
这个 “引用CSS” 是用来装饰html样式，一会儿再说

	<body>
		<h1>Hello World!</h1>
		<h2>Hello World!</h2>
		<p>Hello World!</p>
	</body>
**效果图**
![输入图片描述](README_md_files/cbee2750-d7f3-11ec-9e02-a9ad101d2258.jpeg?v=1&type=image)



	<a href="链接 www.baidu.com" target="_blank">百度</a>
	
这个代码是在表面的字体中里面会隐藏一个链接
就像文章中突出来颜色
![输入图片描述](README_md_files/b4ed85e0-d7f4-11ec-9e02-a9ad101d2258.jpeg?v=1&type=image)

# 接下来就是CSS
# CSS介绍

层叠样式表(英文全称：Cascading Style Sheets)是一种用来表现[HTML](https://baike.baidu.com/item/HTML)（[标准通用标记语言](https://baike.baidu.com/item/%E6%A0%87%E5%87%86%E9%80%9A%E7%94%A8%E6%A0%87%E8%AE%B0%E8%AF%AD%E8%A8%80/6805073)的一个应用）或[XML](https://baike.baidu.com/item/XML)（标准通用标记语言的一个子集）等文件样式的计算机语言。CSS不仅可以静态地修饰网页，还可以配合各种脚本语言动态地对网页各元素进行格式化。

CSS 能够对网页中元素位置的排版进行像素级精确控制，支持几乎所有的字体字号样式，拥有对网页对象和模型样式编辑的能力。

## CSS代码
	.center{  
	    background-color: #f3f3f3;  
	    width: 80%;  
	    margin: auto;  
	}
这个代码引用在HTML，使得HTML更美观
（注：HTML和CSS绑定在一起，就能起效果）

**下面就是效果图**
![输入图片描述](README_md_files/bf607140-d7f9-11ec-b0aa-9b6a46f9d6fd.jpeg?v=1&type=image)

其实CSS比较简单，只是一些思维逻辑性和几个英语单词，看完就能学会！

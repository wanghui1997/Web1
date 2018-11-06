<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
实验十二    石家庄周边游
一、	设计目的
1.熟练掌握HTML在组织结构上的优势。
2.熟练掌握CSS在网页布局中的应用。
3.学习Web标准及浏览器的兼容性。
二、设计步骤
1. 功能性需求分析
该网站共有3个页面，其中每一个页面的屏幕截图及主要功能如下所列。
（1） 首页：
屏幕截图： ![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
图1 首页屏幕截图
（2）内容页： 
图2 内容页屏幕截图![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
（3） 列表页： 
图3 列表页屏幕截图![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
主要实现功能：
首页从全局的角度把网站设计内容进行概括总结，给读者一个全新的认识
导航栏方便网民的查找各项内容
内容页具体的介绍了每一个模块的内容，有详细的内容。
列表页提供了更加全面的新闻列表几个方面的内容，可以进一步的了解网站
2. 搜集网站素材
3. 建立网站代码目录结构（截图给出目录结构）
 
图 文件目录结构
images文件夹存放本实验中用到的图片，css文件统一放到css文件夹中。
4. 编写HTML代码
（1） 首页部分：
整体结构：![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
  
核心源代码： ![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
 
（2） 内容页：![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
 
（3）列表页：![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
 
5. 编写CSS布局及样式
（1） CSS布局：
核心源代码：
 ![Image text](https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg)
 
 

 
核心技术： float  position
Float实现布局：多次使用
Position辅助布局： 使用较少
（2） 添加CSS样式：
通用类属性：
超链接的比较多
  a: hover  a:link   a:active  a:visitied
背景相关类属性：
background-image
background-position
background-color
background-reapet
6. 调试浏览器兼容性
问题记录
1.	问题表现：网页居中问题
2.	问题表现：某些浏览器不支持某些属性
3.	问题表现：不同浏览器的标签默认的外边距和内边距不同
设计总结
1.	需求分析阶段的经验：需要浏览类似功能的网页，学习他们是如何把人们的需求考虑进去的，从网民的角度来思考问题，自己想要在网页里得到哪些东西，如何可以吧人们的需求尽可能多的包含在网页中呢，一定要多学习别人网站的设计，从中分析好的地方与需要改进的地方，最终确定有哪些需求。
2.	编写HTML代码的经验：一定要想找好资料，自己想要在网页中呈现的文字图片，一定要先想好。
3.	 CSS布局的经验：网页要有一个什么样的布局，一定是在自己写网页之前设计好的，不可以边写网页边设计网页布局，这样的话做出来的网页就可能不是那么的好看。无论是做什么事情都要先想好有了目标实现起来就很快了。
4.	设置CSS样式经验：有很多样式的设计是一样的，可以写的更简单一点，避免冗余，减少代码量。
5.	调整浏览器兼容性经验：浏览器的种类太多，人们使用的浏览器也不能一模一样，所以一定要先了解大多是网民使用的是什么浏览器，调试的时候用多种浏览器尝试。每个网页的css最好前面都设置一下通用的选择器
6.	 Sublime Text使用经验：sublime text 不仅可以打开.html的html网页文件，还可以打开.css的css样式文件，它也可以打开.md的Markdown文件，我们在设计网页的时候可以用Markdown文件记录自己设计的网页，包含核心代码，方便日后查看。这三种文件都可以用sublime text打开吧这些放到一起方便查看。他还可以打开文件夹，把所有自己写的网页放到一起，由树状结构图很清晰，内容也可以折叠方便查找错误。
7.	课程小结
1）HTML内容：（补充完整）
2）CSS内容
3）网上参考的内容：查找资料，搜集图片
4）浏览器对CSS的兼容性上的不同表现（你所遇到的）：浏览器的默认网页显示比例大小
解决方案：通过自己多次尝试看不同比例下，不同的效果，查看别人的网页浏览器默认比例大多是多少，通过学习兼容性的相关问题，最终解决自己的问题
参考文献
1.	http://blog.sina.com.cn/lm/top/rank/（看看别人的博客）
2.	http://qzone.qq.com/index.html
3.	CSS盒子模型及DIV布局
4.	浏览器对CSS的兼容性：http://www.div-css.com/html/XHTML-CSS/hack/1136667.html http://www.divcss5.com/css-hack/c23.html http://www.divcss5.com/css-hack/


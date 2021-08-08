# HTML5 页面元素及属性

## ul 元素

## ol 元素

## dl 元素

## 列表的嵌套应用

## header 元素

HTML5中的header元素是一种具有引导和导航作用的结构元素，该元素可以包含所有通常放在页面头部的内容。



## nav 元素

nav元素用于定义导航链接，是HTML5新增的元素，该元素可以将具有导航性质的链接归纳在一个区域中，使页面元素的语义更加明确。



## article 元素

article元素代表文档、页面或者应用程序中与上下文不相关的独立部分，该元素经常被用于定义一篇日志、一条新闻或用户评论等。



## section 元素

section元素用于对网站或应用程序中页面上的内容进行分块，一个section元素通常由内容和标题组成。

不要将section元素用作设置样式的页面容器，那是div的特性。

如果article元素、aside元素或nav元素更符合使用条件，那么不要使用section元素。

没有标题的内容区块不要使用section元素定义。



## aside 元素

aside元素用来定义当前页面或者文章的附属信息部分，它可以包含与当前页面或主要内容相关的引用、侧边栏、广告、导航条等其他类似的有别于主要内容的部分。



## footer 元素

footer元素用于定义一个页面或者区域的底部，它可以包含所有通常放在页面底部的内容。



## figure 和 figcaption 元素

figure元素的内容应该与主内容相关，但如果被删除，也不会对文档流产生影响。figcaption元素用于为figure元素组添加标题，一个figure元素内最多允许使用一个figcaption元素，该元素应该放在figure元素的第一个或者最后一个子元素的位置。



## hgroup 元素

hgroup元素用于将多个标题（主标题和副标题或者子标题）组成一个标题组，通常它与h1~h6元素组合使用。通常，将hgroup元素放在header元素中。

如果只有一个标题元素不建议使用hgroup元素。

当出现一个或者一个以上的标题与元素时，推荐使用hgroup元素作为标题元素。

当一个标题包含副标题、section或者article元素时，建议将hgroup元素和标题相关元素存放到header元素容器中。



## details 和 summary 元素

details元素用于描述文档或文档某个部分的细节。summary元素经常与details 元素配合使用，作为details 元素的第一个子元素，用于为details定义标题。标题是可见的，当用户点击标题时，会显示或隐藏details中的其他内容。



## progress 元素

progress元素用于定义一个正在完成的进度条，这个进度可以是不确定的，只是表示进度正在进行，但是不清楚还有多少工作量没有完成



## meter 元素

meter元素用于表示指定范围内的数值。



## time 元素

time元素用于定义时间或日期，可以代表24小时中的某一时间。time元素不会在浏览器中呈现任何特殊效果，但是该元素以机器可读的方式对日期和时间进行编码。这样，用户能够将生日提醒或其他事件添加到日程表中，搜索引擎也能够生成更智能的搜索结果。



## mark 元素

mark元素的主要功能是在文本中高亮显示某些字符，以引起用户注意。该元素的用法与em和strong有相似之处，但是使用mark元素在突出显示样式时更随意灵活。



## cite 元素

cite元素可以创建一个引用标记，用于对文档参考文献的引用说明，一旦在文档中使用了该标记，被标记的文档内容将以斜体的样式展示在页面中，以区别于段落中的其他字符。



## 全局属性

**全局属性是指在任何元素中都可以使用的属性，在****HTML5****中常用的的全局属性有****draggable****、****hidden****、****spellcheck****和****contenteditable****。**

draggable属性用来定义元素是否可以拖动，该属性有两个值：true和false，默认为false，当值为true时表示元素选中之后可以进行拖动操作，否则不能拖动。

在HTML5中，大多数元素都支持hidden属性，该属性有两个属性值：true和false。当hidden属性取值为true时，元素将会被隐藏，反之则会显示。元素中的内容是通过浏览器创建的，页面装载后允许使用JavaScript脚本将该属性取消，取消后该元素变为可见状态，同时元素中的内容也及时显示出来。

spellcheck属性主要针对于input元素和textarea文本输入框，对用户输入的文本内容进行拼写和语法检查。spellcheck属性有两个值：true（默认值）和false，值为true时检测输入框中的值，反之不检测

contenteditable属性规定是否可编辑元素的内容，但是前提是该元素必须可以获得鼠标焦点并且其内容不是只读的。





## 阶段案例
# Someday's XeLaTex Template

## Someday的XeLaTex中文模板

首先，如果你是初学者，不要一进来就发现是XeLaTex，不是你所想要的Latex，然后就匆匆离开。XeLaTex本身就是LaTex的一个版本，很多命令可以通用，XeLaTex的优点是支持第三方字体。

现在，欢迎你使用Someday出品的Tex模板，因为网上很多模板下载下来根本无法使用，而且最最让人头痛的就是Latex对中文的支持很不友好，所以我采用了XeLaTex，因为可以导入第三方字体。然后我从头学习，从配置到尝试，自己搭建了一个模板，希望对你有帮助，有任何的Bug，及改进意见，欢迎联系作者：someday@buaa.edu.cn



### 模板系统环境：

Someday使用的是Mac系统，Sublime Text2用Package Control安装Latextool插件后进行编译，编译模式为xelatex，可以直接编译。

在www.sharelatex.com网站上也可以直接编译。



### 模板结构：

#### 1、main.tex

main.tex是整个模板的灵魂，所有的宏包导入，格式设置，页面设置请在该文件中完成，模板中已经提供了页面、中文字体、中文字号、页码、页眉页脚、目录、章节标题样式、章节标号等设置选项。并且提供了封面、图片、表格、引入字体，引入文件、插入代码片等样例。

main.tex使用\documentclass{ctexart}作为文档类别的属性，这是Chinese Tex Article的缩写，是一个现成的模板，目录、摘要等关键词的默认语言就是中文。

#### 2、字体文件夹

目录名：fonts

你自己的字体文件直接放在根目录下就可以了，在导言区设置以下命令：



#### 3、图片文件夹

目录名：include_picture

将所需图片放入该目录下，按如下方式使用：



#### 4、引用文章文件夹

目录名：include_tex

将需要引用的.tex文件放入该目录下，注意引用的tex只保留文章内容，不需要导言区以及各种格式设置选项，设置格式请在main.tex中完成，样例可参照在include_tex下的include_section.tex文件。







### 写在最后

作者的一点感言和期许：

1、希望这个模板能对你有帮助，作为使用或者学习的好素材。

2、希望你在使用时保留main.tex前两行的注释：

%Welcome! This is Someday's XeLaTex Template. 
%Developer: Someday

尊重Someday的著作权，Someday就开放使用权~

3、记住，官方的说明文档（Documentation）永远是最好的教程。

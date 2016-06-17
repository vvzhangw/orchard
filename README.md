# orchard
学习orchard笔记
来吧，自己翻官网文档吧：
http://docs.orchardproject.net/en/latest/Documentation/Managing-widgets/?spm=5176.100239.blogcont31954.12.8DcMxd&file=Managing-widgets.ashx
Layers, Zones, and Widgets
在选择层级的时候可以有以下几个选择：
Default是默认的选项，指的是在每一页上面显示
Authenticated是指对已经注册的用户显示出来
Anonymous是指针对陌生的，匿名用户显示出来
Disabled是指不显示，只是占一个层级，保存了当前的widget，但是暂时不显示出来。
TheHomepage是显示在home page上面的
![img](https://github.com/img1.png)

Rule的作用是如果在选择的时候不按照rule来，那么就会不显示（The Layer Rule value is an expression that resolves to either true or false. If it resolves to true, the widget is displayed; otherwise the widget is not displayed.）


Assigning a Widget to a Zone
在zone上点击创建按钮，选择html widget来举例，需要注意的是不管你往里面写了啥，配置的时候zone,layer,title,position都是要选的，position是一个相对的位置，如果你要把几个东西按照一定顺序展示出来，你要确保他们被放在了同一个层，因为zone里面的widget可能来自很多个不一样的层（ The Position field determines the relative position of all widgets within the zone (in effect, z-order). Keep in mind that the widgets within the zone can come from multiple layers. For example, two different layers might have widgets assigned to the same zone.）

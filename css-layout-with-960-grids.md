CSS-LAYOUT-WITH-960-GRIDS
=========================

## 参考文档

	* http://960.gs/

	* http://blog.chinaunix.net/uid-22414998-id-2878529.html CSS 框架960Grid 从入门到精通一步登天

	* http://www.w3cplus.com/css/css-layout-with-960-grids CSS布局--960gs

## 概念性的词语

	1. 容器名称：这里固定网格取名叫“container”，然后针对每小类取名为“container12、container16、container24、container32”；针对自适应网格取名为“containerFluid”，同样针对每小类“containerFluid12、containerFluid16、containerFluid24、containerFluid32”，当然如果只是针对其中一种写页面的化，只需要一个统一的名“container”；
	1. 网格：网格就是将容器分成的份数，其中每一份就称为网格，取名为grid，并且具有“grid1~grid32”。其中使用的是“container”那么对应的最多网格就是“grid12”，其他的依次类推；
	1. 网格宽度（列宽）：这个就是每个网格的宽度了，这个就跟具体的列数和列于列之间的距离很有关系的，
	2. 网格间距：这个是指相邻两个网格之间的距离；
	3. 内容宽度：这个宽度是指内容所占的宽度，这里只有两种情况，一种是内容宽度为“950px”另一种为“940px”。


## 一个实例，960gs 的 12 列为例：

	1. 容器总宽--container12 = 960px；
	2. 网格数--Number of columns = 12；
	3. 网格宽度--Column width = 60px；
	4. 网格之间的距离--Gutter width = 20px; 也就是margin-left:10px;margin-right:10px；
	5. 内容宽度--Content width=940px；
	6. 总宽度--Full width=960px，换句话总是960px。因为我们这里所讨论就是960gs。

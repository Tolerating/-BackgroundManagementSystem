#后台管理系统使用说明
##文件夹说明
	>static中存放的是index.html页面的样式文件和js文件
	>lib中存放的是第三方插件
*********

##关于HTML代码
*头部区域
	>`<nav class="header">后台管理系统模板</nav>`
	头部区域可以自己定义,如要更改其高度,请注意更改index.css文件中的以下样式:
	>>.aside样式中的top值
	>>.content .content-header样式中的top值
	>>.content样式中的top值

********

*侧边栏
	>这里的代码统一为:
	```
	<div class="aside-option">
		<label for="option1">用户<i class="glyphicon glyphicon-chevron-down"></i></label>
		<input type="radio" name="option" id="option1" checked="checked"/>           
		<ul>
			<li data-href="./1.html"><a href="javascript:void(0)">用户管理</a></li>
		</ul>
	</div>
	```
	请注意label标签中的for要与input标签中的id值保持一致
	ul下的li标签写法与代码中的保持一致,不然会报错
	如果要修改侧边的的宽度,请注意更改index.css文件中的以下样式:
	>>.aside样式中的left值
	>>.content .content-header样式中的left值
	>>.content样式中的left值

*选项卡区域
	>css代码在index.css中的页面选项卡注释区域
	>如要修改其高度,请注意更改index.css文件中的以下样式:
	>>.content样式中的top值


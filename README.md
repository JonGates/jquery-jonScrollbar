jonScrollbar 
===========
jon jquery scrollbar plugin
滚动条控件，兼容所有浏览器！


Usage
-----------
Refer to the [demo](#) and the [source code](https://github.com/JonGates/jquery-jonScrollbar/tree/master/script/)

### jquery 对象级调用
	<div id="cs1"><div><br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/>1<br/></div></div>
	<div id="cs2"><br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/>2<br/></div>
	<script type="text/javascript">
		(function($){
			$('#cs1').jonScrollbar({'theme':'light1'});
			$('#cs2').jonScrollbar({'theme':'light2'});

			$('#cs1').jonScrollbar('scrollTo','0');
			$('#cs2').jonScrollbar('scrollTo','last');
			$('#cs1').jonScrollbar('scrollTo','50');
		})(jQuery);
	</script>

### 以后版本介绍：
　　v.0.0.0.2　将支持X轴滚动和自由模式
　　v.0.0.0.3　很多同学需要瀑布流方式，为了减少DOM的大小，插件将支持回调
　　

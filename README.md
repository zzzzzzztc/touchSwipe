# touchSwipe v1.0
移动端滑动组件 touchSwipe
>更新信息

2015-01-16
+ 第一个版本上线
+ 添加了横向和纵向滑动的方向选择功能
+ 适用于Android和IOS系统，wp系统暂时不支持，在下个版本会增加对ie的支持

>简介

+ 这是适用于移动端的一款滑动组件
+ 使用场景一般多在移动端的单页展示上，例如微信的场景秀

>基本用法

1.首先先引入组件的javascript文件，该组件不依赖于任何js类库

		<script src="touchSwipe.js"></script>
        
2.基本HTML结构如下：要保证类名的准确无误

		<!-- touchSwipe start -->
		<div class="swipe">
			<ul class="t-swipe">
				<li class="swipe-list swipe-list-1">
				</li>
				<li class="swipe-list swipe-list-2">
				</li>
				<li class="swipe-list swipe-list-3">
				</li>
			</ul>
		</div>
	    <!-- touchSwipe stop -->
        
 3.调用方法：
 在刚刚引入的script文件下一行键入
 
 		touchSwipe({
			'show':true,
			'transTime':.3,
			'transType':'ease-in',
			'direction':'Y'
		});
        
 >参数说明
 
 + show
 
 		默认值为true  用于是否启用
        
 + transTime
 
 		默认值为.3  用于调节页面滑动速度
        
 + transType
 
 		默认值为ease  用于调节平滑滚动类型
        
 + direction
 
 		默认值为Y  用于调节滑动方向

>demo预览地址（扫描二维码查看）

![测试二维码](http://www.wangwenyu.com//content/images/2015/01/ZWB7H-S4-9--BWG-U4--COJ.jpg)

#### flexbox 布局
 今天主要学习了Flexbox 布局，CSS3 中的一个新的布局模式，目的是解决复杂的现代web布局。  

+ Flexbox 包含Flex Containers 与 Flex Items  
	- Flex Containers `display: flex/inline-flex`  
	- Flex Item 就是Flex Containers 的子元素，类似bootstrap中的栅格系统  
	- 在Flex Containers外面与Flex Item里面的Dom元素还是与以前一样的渲染  
	- 可以设置Page 的direction，例如rtl  
	- Main Axis，Cross Axis类似于坐标系中的x与y轴，但是方向是可以改变的，默认的是从上往下，从左往右。
+ Flex Containers 的属性  
	- flex-direction 就可以来改变 Axis的方向，默认值为row，其他的值还有row-reverse, column, column-reverse, 此处可以参看demo  
	- justify-content 用来调整在Main Axis的位置，可能的值有flex-start、flex-end、center、space-between与space-around  
	- align-items 用来调整Cross Axis的位置，可能的值有flex-start (default)、flex-end、center、baseline、stretch  
	- flex-wrap： wrap 可以设置Flex Containers 变为 multiple Flex Lines，即变成多行，默认情况是一直在一行中    
	- align-content 与align-items类似，但是是来调整Flex lines的  
	- flex-flow： 是flex-direction与flex-wrap的简写
+ Flex Items 的属性
	- 一个Flex Item是指Flex Containers的直接孩子   
	- order 设置某一个Flex Item 的次序，为-1 时会首先被显示  
	- margin 设置为auto时会将额外的空白都吸收    
	- align-self 类似align-items  
	- flex: [number] 用来指定items所占的比例，如果每一个flex item都设置flex：１，那么空白的地方就都会被分配
+ 利用align-items justify-content可以实现居中对齐  
 
		.demo {
		  height: 300px;
		  display: -webkit-flex;
		  display:         flex;
		  -webkit-align-items: center;
		          align-items: center;
		  -webkit-justify-content: center;
		          justify-content: center;
		}

+ [demo](https://github.com/lihang1870719/flexbox)
+ [参考资料](https://bocoup.com/weblog/dive-into-flexbox/) 
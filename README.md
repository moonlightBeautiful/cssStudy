# cssStudy
1.css hello
2.css 基础
    1.基本语法
        选择器{属性:值;属性:值}
    2.选择器
        1.标记选择器
        2.类别选择器
        3.id选择器
    3.样式
        1.行内样式：标签的style属性
        2.内嵌式：
        3.链接式：会先指向css文件，然后一边加载html标签，一边加载用到的css样式。不会一次把css样式全部加载下来。
        4.导入式：一次把css样式全部加载下来。
        优先级比较：
            行内样式>(内嵌式、链接式、导入式根据顺序会变)
            一般的在网页中的顺序都是行内样式、链接式、内嵌式、不使用导入式，导入式会影响性能。
                这样的优先级就是：行内样式>内嵌式>链接式
3.css 网站小实践
4.css 高级特性
    1.复合选择器
        1.1交集选择器：标记.类{}
        1.2并集选择器：基本选择器,基本选择器{}
        1.3后代选择器：基本选择器 空格 基本选择器{}
        1.4子选择器：基本选择器 > 基本选择器{}
        1.5相邻弟弟选择器：基本选择器哥哥 + 基本选择器弟弟 {}
    2.继承特性:
        大多数样式是可以继承的
    3.层叠特性：
        行内样式>ID样式>类别样式>标记样式
5.css 盒模型
    1.简介：边框、内边距、外边距(相邻外边距垂直取最大值，左右相加，)
    2.标准文档流：在不使用css相关的排列与定位时，各种元素的排列规则。
        2.1.块级元素（左右撑满，同级上下排列）和行内元素（同级左右排列，排满后自动换行）
        2.2.相邻外边距计算：垂直取最大值，左右相加。
        2.3.嵌套外边距：子块的外边距以父块的内容为参考，margin不能被继承。可以设置成负值。
6.css 样式
    1.文本样式：字体，文字，文本框
    2.图片样式：边框 图片大小 图文混排
    3.背景样式：颜色 图像 平铺（默认左右铺完，上下铺） 取消平铺 距离左边 上边距离 固定位置 图片滚动
    4.表格样式：鼠标移动到行触发事件 边框 宽度 布局
    5.超链接样式：链接4种状态 
    6.列表样式：列表符号 图片
7.css 位置
    float、display、position、z-index、display
    float：如果不指定大小，则大小变为实际内容的大小。
    position：
        absolute，定位根据第一个父包含块定位。从标准流中脱离出来。
            包含块：元素一旦定义了定位（相对、绝对、固定）就是包含块了，根元素html是初始包含块。
        fixed，相对浏览器定位，当于上了一层了。
        relative，定位根据原本的位置定位。
    z-index：
        一般和position配合使用
8.css 布局
   绝对定位法和浮动定位法
   宽度可以直接直接设置百分比，一般就是默认浏览器宽度的长度或者父的长度。
   高度设置百分比，父必须有明确的高度
   
   
   
   
   垂直方向上的定位：
   z-index:  numpx    
   -1px的话，会在其他元素的底层，
                       1的话会覆盖其他元素，也就上上层。
   改变元素内联和块     
          display：
   inline 	//把元素变为行内元素
   block 	//把元素变为块级元素
   none：	元素不会显示
    
# cssStudy
hello
    1.文本样式
        字体：如果前面的字体浏览器没有，则顺序找，找到哪个是哪个
            font-family: "Times New Roman", Arial;
        字体样式：比如倾斜
            font-style: italic;
        字体加粗：默认不加粗 normal 
            font-weight: bold;
        单词字母大小写转换：
            text-transform: capitalize;  首字母大写
                uppercase大写转换 lowercase小写转换
        文字大小
            font-size: 26px;
        文字装饰效果
            /*文字横线 none默认 underline下划线 line-through横线 overline上划线*/
                        text-decoration: line-through;
        段落首行缩进
             /* 首行缩进em代表一个汉字的距离 */
            text-indent: 2em;
        单词间距
            word-spacing: 20px;
        字母间距
            letter-spacing: 2px;
        行间距
            /* 文字行高，默认1.2,行高是文字高度的1.2倍。 */
                        line-height: 1.5;
        文字颜色
            color: blue;
        文字水平位置，默认left 右right 居中center 两端对齐justify
            text-align: justify
        边框 宽度 颜色 形式
            border: 1px red solid;
        边框间距
            margin
        文字距边框距离
            padding
        背景色
            background-color
    2.图片样式
        vertical-align 图片垂直方向的位置，也可以用于文本
    3.背景颜色和背景图片
    4.表格样式
        给table标签加border边框，td单元格不会有，所以需要 table td { border边框 }。border不能继承。
        border-collapse：边框是合并collapse还是分离separate。
        border-spacing: 边框与边框的距离
        table-layout：表格宽度，默认值auto，根据表格内容，表格大小自动调整大小。with不管用。fixed，固定with宽度。
        note：表格的高度，很难把握。不管怎么设置，不会低于最小要求。大于最小要求，则按大于的值来算，
    5.列表样式 
        列表符号list-style-type 默认实心圆圈和数字，none没有 circle圆圈 square方块
        列表图片符号list-style-image   url("./li.png")
        
        
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
        1.2并集选择器：标记,类{}
        1.3后代选择器：标记或者类 空格 标记或者类{}
        1.4子选择器：标记或者类 > 标记或者类{}
    2.继承特性:
        大多数样式是可以继承的
    3.层叠特性：
        行内样式>ID样式>类别样式>标记样式
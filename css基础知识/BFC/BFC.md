#什么是 BFC？
CSS BFC，Block Formatting Context，块级格式化上下文，是页面上用于渲染 CSS 的一个区域，相当于一个小型的布局，块级元素和浮动元素会根据这块区域进行布局

#BFC 的作用：

1. 清除浮动
2. 清除浮动，解决浮动导致元素高度塌陷的问题
3. 避免边距塌陷

#创建 BFC：

1. `<html /> ` 根元素。
2. 设置了 float 属性的元素。
3. 绝对定位的元素，position: absolute。
4. 设置 display: inline-block。
5. 设置 overflow: scroll 或 hidden
6. Flex 和 Grid 布局的子元素（非 flex 和 grid 布局容器本身）。
7. ...
   主动创建 BFC,设置 overflow: hidden 和 display: flow-root 是最常用的方法。

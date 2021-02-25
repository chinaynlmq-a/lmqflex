# lmqflex
将根据已有的meta标签来设置缩放比例,通过html根元素来设置，基本元素，从而设置rem的算法

# github
 https://github.com/chinaynlmq-a/lmqflex.git

 # 补充相关依赖包
 无
 # 安装 
 npm i lmqflex
 # 使用
 ```javascript
  import 'lmqflex';
 ``` 
 # 预编样式
```css
 @base-font-size: 75;     //基于视觉稿横屏尺寸/100得出的基准font-size
 @px2rem: @base-font-size * 1rem;
 ```
 如宽度：100px 的设计效果图
 width：100/@px2rem
 # 在实际开发中的作用
 - 引入即可
 - 配合less 或者 sass 来计算
 - 
 - 
 - 


传统布局
繁琐

flex弹性布局
布局简单
flex布局原理
flex是flexible box的缩写，意思为弹性布局，用来为盒模型提供最大的灵活性，
任何一个模型都可以指定为flex布局

flex常见父项属性
## flex-direction:设置主轴的方向
1.主轴和侧轴 
row 默认值从左到右
row-reverse 从右到左
flex-direction: column;
默认值从上到下
flex-direction: column-reverse;
从下到上
column默认值从上到下
column-reverse 从下到上

## justify-content:设置**主轴**上子元素的排列方式
center 居中
flex-start 从主轴的起始位置开始
flex-end 从主轴的结束位置开始
space-around 平分剩余空间
space-between 先两边贴边，再平分剩余空间
## flex-wrap:设置主轴子元素是否换行
flex布局中默认不换行，装不下会缩小子元素的宽度，放到父元素里面，挤进去
nowrap 不换行
wrap 换行
## align-items:设置**侧轴**上的子元素排列方式 （单行）
center 居中
flex-start 从主轴的起始位置开始
flex-end 从主轴的结束位置开始
space-around 平分剩余空间
space-between 先两边贴边，再平分剩余空间
## align-content:设置**侧轴**上的子元素的排列方式（多行）
只能用于子元素换行

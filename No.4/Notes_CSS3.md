# 背景

## background-origin

指定背景图片 background-image 属性的原点位置的背景相对区域,_当使用 background-attachment 为 fixed 时，该属性将被忽略不起作用_.

## background-clip

设置元素的背景（背景图片或颜色）是否延伸到边框下面。

- border-box 背景延伸到边框外沿（但是在边框之下）。
- padding-box 边框下面没有背景，即背景延伸到内边距外沿。
- content-box 背景裁剪到内容区 (content-box) 外沿。

## backface-visibility

backface-visibility 属性指定当元素背面朝向观察者时是否可见。元素的背面总是透明的，当其朝向观察者时，显示正面的镜像。

在某些情况下，我们不希望元素内容在背面可见，比如实现翻牌效果。

因为 2D 变换无透视效果，故该属性对 2D 变换无效。

# 文字

## @font-face

能够加载服务器端的字体文件，让客户端显示客户端所没有安装的字体。

语法：

```CSS
@font-face {
    font-family: <YourWebFontName>;
    src: <source> [<format>][,<source> [<format>]]*;
    [font-weight: <weight>];
    [font-style: <style>];
}
```

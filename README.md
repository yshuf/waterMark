# waterMark
基于jquery的页面水印插件，可以使用多个水印文字，并且每行错开
## 使用方法
```javascript
$('body').watermark({
    texts : [new Date().getTime()], //水印文字
    textColor : "#d2d2d2", //文字颜色
    textFont : '14px 微软雅黑', //字体
    width : 100, //水印文字的水平间距
    height : 100,  //水印文字的高度间距（低于文字高度会被替代）
    textRotate : -30 //-90到0， 负数值，不包含-90
});
```
## 效果图

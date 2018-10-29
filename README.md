# simple-flexible

mobile frontend simple rem responsive code
兼容UC竖屏转横屏，手淘那个lib-flexible.js有bug.可以简单使用我这个。

[项目介绍](http://caibaojian.com/simple-flexible.html)

## How to usage

复制整个文件代码，放在网页的head中。
不需要定义body的font-size值。

设置<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0"> 

PX与REM的转换(区别于手淘版)

1rem = 100px

假如你有一个块是.box{width:120px;height:80px;} 转为rem则为.box{width:1.2rem; height:.8rem;}

生产使用flexible-min.js

另外还需要根据你的设计稿的大小来调整脚本最后的两个参数。

})(640, 640);

第一个参数是设计稿的宽度，一般设计稿有640，或者是750，你可以根据实际调整
第二个参数则是设置制作的最大宽度，超过640，则以640为最大限制。

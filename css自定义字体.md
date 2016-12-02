使用@font-face自定义字体
======================

```
@font-face{
font-family:xujinglei;		/*本地相对路径*/
src:url('xujinglei.ttf'),	/*本地相对路径*/
url('xujinglei.eot');   /*IE9+*/
}
```

* 调用 给相应的元素 添加字体，font-family:xujinglei;

------------------

金属质感文字
============
* 样式代码
>
```
 <style type="text/css">
  p{
  color:white;
  background:black;
  font-weight:bold;
  font-size:30px;
  position:relative;
  }
  span.cover{
  width:100%;
  height:100%;
  position:absolute;
  background:linear-gradient(to bottom,black 0%,transparent 50%,black);
  opacity:0.5;
  }
  </style>
```
* HTML代码
>
```<p><span class="cover"></span>金属质感文字</p>
```


自定义文本被选中样式
=================

``` 
::selection{   /* 文本被选中的状态 */
color: #ff0000;
background:#a9a9a9;
}
::-moz-selection{
color:#ff0000;
background:#a9a9a9;
}
 ```





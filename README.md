# HTML5 学习总结
### 1.程序结构
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>基本的格式</title>
    </head>

    <body>
        链接到<a href="http://www.baidu.com">“百度”</a>
    </body>
</html>
```
其中，body中是显示在页面中的内容，这个例子的显示如下图所示：
![链接到百度](https://github.com/LiuJLin/html_/blob/master/resource/readme_1.png)
### 2.超链接与路径
##### 外部网站链接
上面示例中
```html
 链接到<a href="http://www.baidu.com">“百度”</a>
```
这个语句中用到的就是超链接，可以链接到该网址，此外，还有其他的链接方式。
##### 通过本地路径
* 绝对路径：
```html
 <a href="file:///D:/html/hyperlink.html">hyperlink.html</a>
```
* 相对路径：
```html
<a href="./hyperlink.html" target="_blank">hyperlink.html</a>
```
##### 页面内的链接与跳转
```html
<a href="#1">Day 1</a><br>
<a href="#2">Day 2</a><br>
<a href="#3">Day 3</a><br>
<br><br><br><br><br>
<a name="1"></a>Day 1
<br><br><br><br><br>
<a name="2"></a>Day 2
<br><br><br><br><br>
<a id="3"></a>Day 3
<br><br><br><br><br>
```
### 3.分组
* <p\>  段落，各段落间间距明显
* <div\> 通用分组，分组间的间距不明显
* <blockquote\> 块引用，此块会有明显的缩进，以表示引用
* <pre\> 按照编辑器中的格式进行显示
* <ul\> 无序列表
* <ol\> 有序列表
* <dl\> <dt\> <dd\> 文件列表
* <figure\> 图片  

详见**fenzu.html** 文件，打开浏览器运行看效果。

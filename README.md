# MouseClickEffect
鼠标点击心形或文字展示效果，适配jq页面和vue页面。

心形效果：
![image](https://img-blog.csdnimg.cn/20201012223804526.png)
文字效果：
![image](https://img-blog.csdnimg.cn/20201012223804524.png)


引入方法：

1.单页面引入
```javascript
<script src="../js/heart.js"></script>
```

2.jq项目在公共js中引入
```javascript
document.write("<script src='../js/heart.js'></script>");
```

3.vue项目中引入
js文件放在/srv/assets文件夹下，在main.js文件中引入
```javascript
import './assets/words.js';
```

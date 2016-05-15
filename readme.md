#简单的jquery练习


## 学习记录
### 基本语法：

![基本语法：](image/1.png)


### 文档准备就绪：

![文档准备就绪：](image/2.png)


### 简单的选择器：
![简单的选择器：](image/3.png)


### 注意：

![注意：](image/4.png)


### 简单时间处理函数：

![简单时间处理函数：](image/5.png)


### toggle简单使用：

![toggle简单使用：](image/6.png)


#### 代码实现：
```html
<!DOCTYPE html>
<html>
<head>
<script src="/jquery/jquery-1.11.1.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){
  $("button").click(function(){
  $("p").toggle();
  });
});
</script>
</head>
<body>
<button type="button">切换</button>
<p>这是一个段落。</p>
<p>这是另一个段落。</p>
</body>
</html>
```


### jquery中ajax的使用

![基本语法：](image/7.png)


### get和post请求

![基本语法：](image/8.png)


## 学习jquery的网站
[W3Cschool的jquery学习](http://www.w3school.com.cn/jquery/index.asp)
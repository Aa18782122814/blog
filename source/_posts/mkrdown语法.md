---
title: mkrdown语法
date: 2018-12-25 09:46:48
tags:
- hexo
- gethub
- 域名
categories:
- 教程
- 语法
- 字体
cover_picture: /images/blog.jpg
---
# 标题相关
## 二级标题
### 三级标题
......
###### 六级标题

# 字体加粗
要加粗的字体左右用两个*号包裹  例如：
**字体加粗效果**

## 字体倾斜  斜体
文本左右用一个*包裹

*字体斜体效果*

# 加粗倾斜
左右分别三个*包裹

***加粗倾斜***

# 删除线
左右用2个～线包裹

# 分割线
三个或者三个以上的-或者*

----

# 超链接
[跳转到百度](http://www.baidu.com)
[链接内容]+(目标地址)

# 图片
![图片的alt](图片的src)
alt：图片加载失败的显示文字
src：图片的链接/路径
![表情包](http://www.doutula.com/output/1225/output_1545703876.gif)

# 图片超链接
[![表情包](http://www.doutula.com/output/1225/output_1545703876.gif)
](http://www.baidu.com)

# 代码块/代码片段
```javascript
for(let i = 0;i < 5;i++){
    console,log(i);
}
```
```html
<img src="/[表情包](http://www.doutula.com/output/1225/output_1545703876.gif)" alt="表情包">
```

# 列表
无序列表用-.+.*开始
- 列表1
- 列表2
- 列表3

# 有序列表

1. 列表1
2. 列表2
3. 列表3

# 表格

姓名|性别|课程方向
-|-|-
张三|男|web前端
李四|女|ui
王麻子|男|linux云计算


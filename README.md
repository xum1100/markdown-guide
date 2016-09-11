# markdown-guide
# mardown使用指南
链接直接写上URL就行http://blog.csdn.net/kaitiren/article/details/38513715
#一级标题，标题前面1个\#号
##二级标题，标题前面2个\#号
###三级标题，标题前面3个\#号
####四级标题，标题前面4个\#号
#####五级标题，标题前面5个\#号
######六级标题，标题前面6个\#号
大标题，标题下一行=号（至少1个），效果等同于一级标题
===
中标题，标题下一行-号（至少1个），效果等同于二级标题
---
文字正常大小，但要求有下划横线，只需要在文字和\=号(至少1个)或\-号（至少1个）补空行

===
普通文本换行不能直接回车<br>
需要使用\<br>。<br>
 普通文本汉字半角输入行首空格缩进无效<br>
　普通文本汉字全角输入行首空格缩进有效<br>
    文本前加两个tab实现单行文本
    文本前加两个tab实现单行文本<br>
Think `you`,please call me  `coder`.文字高亮突出显示，用``包围起来，注意不是单引号，是tab上方，数字1左边的按键，英文输入法。<br>
文字的超链接，[我的github](http://www.github.com/xum1100 "鼠标悬停显示的文本")<br>
\*+空格代表圆点表示层级
* 姓名：余罪
* 别名：余小二
* 英文名：rocky
 * 加一个tab表示二级圆点
   * 加两个tab表示三级圆点<br>
>层级1
>>层级2
>>>层级3
>>>>层级4
>>>>>层级5<br>
##插入网络图片<br>
![baidu](https://www.baidu.com/img/baidu_jgylogo3.gif "百度logo")<br>
##插入github上的图片<br>
![git and github](https://github.com/xum1100/git-github-summary/raw/master/github.jpeg "思维导图")<br>
##给图片加上超链接<br>
[![baidu]](http://www.baidu.com) 
[baidu]:https://www.baidu.com/img/baidu_jgylogo3.gif "百度logo"
<br>
<br>
<br>
# markdown语法 #
## 参考资料 ##
https://www.zhihu.com/question/20409634  
简明版[markdown语法说明(简体中文版)](http://wowubuntu.com/markdown/basic.html)  
完整版[markdown语法说明(简体中文版)](http://wowubuntu.com/markdown/index.html)
# 一级标题 #
## 二级标题 ##
### 三级标题 ###
#### 四级标题 ####
##### 五级标题 #####
###### 六级标题 ######
大标题
===
中标题
---
文字正常大小，有下划横线  
s
===
普通文本换行  
用空格空格回车换行  
　文本前全角输入空格有效  
*强调，相当于em*  
_强调，相当于strong_
## 无序列表 ##
* 列表项1
* 列表项2
* 列表项3
    * 列表项3.1
    * 列表项3.2
        * 列表项3.2.1
+ 列表项1
+ 列表项目2
+ 列表项3
    + 列表项3.1
        + 列表项3.1.1 
- 列表项1
- 列表项2
- 列表项3
    - 列表项3.1
        - 列表项3.1.1
## 有序列表 ##
1. 列表项1
2. 列表项2
3. 列表项3
## 链接 ##
http://www.baidu.com
## 文本超链接 ##
[百度](http://www.baidu.com "百度一下你就知道")
## 图片超链接 ##
[![baidu]](http://www.baidu.com) [baidu]:https://www.baidu.com/img/baidu_jgylogo3.gif "百度logo"  
## 插入网络图片 ##
![baidi](https://www.baidu.com/img/baidu_jgylogo3.gif "百度 logo")  
## 插入github上的图片 ##
![github](https://www.github.com/xum1100/git-github-summary/raw/master/github.jpeg "a chart about git")  
>单行文本

>单行文本

>单行文本

## 代码块 ##
```javascript
document.getElementById("banner").innerHTML = "Hello world"
```
## 文本高亮凸显 ##
Thank `you`,welcome to `HangZhou`.  

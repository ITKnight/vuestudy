# vuestudy

这是在我在学习VUE的一个小项目。
##文件说明
index.html:主要实现了双向绑定【目标已经达成】

##目前遇到的问题
希望实现 VUE中Ueditor的数据绑定 【正在进行的难点】
### 解决方案1
*  watch currentIndex 当他改变时候，将对应article的内容放进editor
*  listen editor的contentChange事件，对应塞数据给article

#vuestudy

this project is create for my vue study step by step.
## files
index.html: goal to bind data and is achieved

##current problem
vuevsueditor.html: bind data with ueditor 
### soLution 1:
* watch var currentIndex and when it changes ,send content to the editor
* listen editor's contentChange envent when it fires ,send the content to the var articles
ueditor offical site:http://fex.baidu.com/ueditor/

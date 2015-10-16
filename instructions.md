
# drag
可以控制拖动范围，原生js书写
//参数配饰
#g("ui_main")拖动的文件，g("ui_title")点击拖动区域可以自设置,改变g()中参数就行了，g()获取的是元素的id
loca(g("ui_main"),g("ui_title"));       			  

#这个是控制浏览器大小改变时也执行
window.onresize=function(){

loca(g("ui_main"),g("ui_title"));

}

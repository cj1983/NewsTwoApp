NewsTwoApp
==========

模仿网易新闻的UI框架versions2

---------------------------华丽丽的分割线------------------------------

beta 0.2

1、添加了回收抽屉的接口

2、增加下面的在左菜单跳转新页面时回收抽屉的API

－(void)closeSideBarWithAnimate:(BOOL)bAnimate complete:(void(^)(BOOL finished))complete;
 
3、适配iOS8无法传递滑动事件到superview。（增加TouchPropagatedScrollView来解决）

---------------------------华丽丽的分割线------------------------------

beta 0.1

1、UI只适配到iOS7以上的效果

2、区别于第一版，这里使用的是手势来实现效果，比较传统的做法，当然这都是借鉴其他人的成果，里面关键代码也是借鉴过来的哈

3、加入页面跳转和手势返回的效果

##练习项目-ajax动画名句(link:https://arinu.github.io/Hitokoto/)

###代码在此link:https://github.com/Arinu/Hitokoto

这个也是在FCC上漏掉的项目，还有好几个

都是小项目，到时一起给整合到练习项目集里头

初次使用ajax

也没有使用JQuery，还是用原生js写的


###**17/11**

编写了兼容ie的事件代码

并添加了<code>noscript</code>标签提示默认禁用js脚本的用户启动脚本或更换浏览器

因为最近把系统降级到win7。发现自带的ie8居然默认禁用js脚本···

添加定时刷新逻辑，其实这个很早以前就写好了，只是没处理好点击按钮时清理定时器的逻辑。

由于昨天一时兴起又添加了一个进度条。这也是一开始就像添加后来没去动手的一个遗憾。

之后花了点时间处理清理定时器的逻辑，可惜无果（因为脑袋不好）

今天突然想起了一个可能解决问题的方法，所以立即动手编写，之后定时器的问题，就算是解决了。

进度条的逻辑，由于使用css的<code>transition</code>属性，ie8及以下均不支持动画。

虽然应该可以使用js来实现，但是比较懒23333。。。
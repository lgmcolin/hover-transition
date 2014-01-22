#jquery-hoverTransition

[点击查看demo](http://lgmrain.github.io/demos/jquery.hoverTransition.html)

单纯用`css3`也可以实现,不过考虑到兼容性方面至少得支持`css3 transition`, [css3 demo](http://pigrun.github.io/1st_run/demos/pfhe/css-hover-direction.html)

##用法

- 参数：`options`,`item`((可选,默认div))
- 选定一个元素作为`hover`的触发对象,使用`hoverTransition`

如:

```	
var options = {speedTime:300};
$('div-parent').hoverTransitionBegin(options,'div');
```	

##说明

需要`import modernizr.js`检测是否支持css3 transition,可以根据情况使用代码段检测去掉modernizr.js

`hoverTransition`使用options参数介绍:
- `speedTime` 指定覆盖层的速度
- `easing`    覆盖层的运动方式
- `hoverDelay`延迟执行的时间

## 更新日志

### 0.1（2014-01-10）

- 整理代码API，编写文档，开源到github
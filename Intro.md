### 0.7.0(151225)

根据网友提议，默认内容过少时，自动触发加载下方内容，只会加载一次，如果内容还不够一屏，无法继续触发。并且修复`lock()`，增加参数可以手动锁定上方或者下方。

### 0.6.0(151218)

根据网友提议，增加提前加载距离threshold，适用于上拉加载更多功能。默认显示到加载区高度2/3时加载。

### 0.5.0(151217)

感谢交流群里网友各种吐槽上拉加载抖动。发现`touch`和`scroll`同时作用会发生抖动，干脆把上拉加载改为滑到底部自动加载。如依旧需要上拉加载效果，可以下载[releases0.4.0版本](https://github.com/ximan/dropload/releases/tag/0.4.0)。

### 0.4.0(150927)

根据网友提供demo，修改至适用大部分普通列表网页，终于可以大规模使用啦！

### 0.3.0(150410)

项目中通知列表有可编辑、删除等状态，需要锁定和解锁下拉刷新功能。

### 0.2.0(150325)

公司项目APP内嵌页需要下拉刷新，终于可以实战了！这一版大家可以开始使用和反馈。

### 0.1.0(141024)

虽然有**上拉加载更多**的需求，但一直都是用的scroll方法。写**dropload**完全是为了练习插件写法和touch的使用。
# Shared-Route

### Introduction

New way to explore your campus life.

### Project Progress

**10.13**

完成了所有页面的跳转逻辑，动画等，下一步要修改各种recyclerview的框架为swipe refresh.

**10.20**

1. 完成了寻找需求页面到购物车的传值。
2. 服务端的severlet完成，现在有一个本地服务器，基于这个本地服务器我们实现了网络登录的Demo，这里放出来demo，里面的Async框架和Post方法可供入门学习。


**10.21**

Task：

- [x] 使用sqlite数据库作为本地缓存，将所有页面更改为读取数据库的形式。——阿臻


- [x] Login 页面接入网络请求。——李博


Bug：

- [ ] Login 页面所需要的版本过高，在低版本手机上闪退。——一鸣​


**10.22**

Task：

- [x] 完成发布需求upload task到云端，以及修改页面UI——武德浩
- [x] 完成寻找需求的从数据库fetch信息的操作，完成了利用缓存实现默认登录的效果——李博


Comment:

现在一鸣和志宇都在准备考试，服务器那边的工作暂时闲置，周日我们（阿臻，我，浩哥）主要完成了一些本地功能的完善和修改，以及UI的修改。

接下来还需要考虑的重点在服务器端的逻辑设计上，等到周三晚上可以开始重新设计。

还有一点在于页面的下拉刷新，上拉加载的效果与网络请求的衔接，这里找到了一个很合适的模板，正在进行接入。














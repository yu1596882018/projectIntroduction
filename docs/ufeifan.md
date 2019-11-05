#### ufeifan开发与重构（pc端与移动端）
+ 网页地址：
    + pc端：[http://test.ufeifan.com/](http://www.ufeifan.com/)
    + 移动端：[https://m.ufeifan.com/](https://m.ufeifan.com/)
+ 项目简介：B2C机票交易平台，类似携程、去哪儿的机票预订平台，分为pc端和移动端。其中pc端只重构了部分的页面，移动端项目进行了整体重构。
    + pc端：兼容至ie8、以jQuery为主、拥有较多机票业务复用组件、由前后端未分离，转向前后端半分离
    + 移动端：以vue为主、webpack脚手架从0到1搭建、拥有较多移动端机票业务复用组件，如：日期选择、日历选择、机场城市选择、国籍选择等等；
+ 技术组成：
    + pc端：jQuery + artTemplate + 原生js等；
    + 移动端：webpack + vue + axios + 原生js + rem等；
+ 我的职责：
    + pc端：日常开发与维护、部分页面重构、组件封装、性能优化
    + 移动端：项目重构、脚手架搭建、组件封装、规划项目交互与用户体验等
+ 截图预览：
    + pc端：
        + ![首页](http://cms-hdgg.jschengta.com/images/ufeifan-pc-01.jpg)
        + ![机票列表页](http://cms-hdgg.jschengta.com/images/ufeifan-pc-02.png)
        + ![机票详情页](http://cms-hdgg.jschengta.com/images/ufeifan-pc-03.png)
        + 重构页：![下单页1](http://cms-hdgg.jschengta.com/images/ufeifan-pc-04.png)
        + 重构页：![下单页2](http://cms-hdgg.jschengta.com/images/ufeifan-pc-05.png)
        + 重构页：![支付页](http://cms-hdgg.jschengta.com/images/ufeifan-pc-06.png)
        
    + 移动端：
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-01.png" alt="首页" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-02.png" alt="机票列表页-去程" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-03.png" alt="机票列表页-返程" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-04.png" alt="机票详情页" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-05.png" alt="下单页1" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-06.png" alt="下单页2" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-mobile-07.png" alt="支付页" width="375px"/>
    + 我封装的组件：
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-component-01.png" alt="日历选择组件" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-component-02.png" alt="城市选择组件1" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-component-03.png" alt="城市选择组件2" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-component-04.png" alt="滚动选择组件-日期" width="375px"/>
        + <img src="http://cms-hdgg.jschengta.com/images/ufeifan-component-05.png" alt="滚动选择组件-签发地" width="375px"/>
        + ![select UI组件 与input UI组件](http://cms-hdgg.jschengta.com/images/ufeifan-component-06.png)
        + ![select UI组件2](http://cms-hdgg.jschengta.com/images/ufeifan-component-07.png)

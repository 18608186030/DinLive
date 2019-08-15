# DinLive
**APP描述**
## 技术要点  
kotlin、组件化、rxjava2、retrofit2、tinker、视频播放、腾讯TBS文件阅读、ARouter  
项目采用MVC、MVVM两种开发模式，根据业务进行组件化开发、通过ARouter进行页面跳转和数据交互  

- 组件化框架：[CC](https://qibilly.com/CC-website)
- 模块间路由、通信，解耦：[ARouter](https://github.com/alibaba/ARouter/blob/master/README_CN.md)
- 崩溃手机、热更新方案：[bugly、tinker](https://bugly.qq.com/docs/)
- 屏幕适配方案：[AndroidAutoSize](https://github.com/JessYanCoding/AndroidAutoSize/blob/master/README-zh.md)
- 视屏播放器：[GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)
- 网络请求框架：[RxEasyHttp](https://github.com/zhou-you/RxEasyHttp) retrofit2+okhttp3+rxjava2二次封装
- 图片加载：Glide V4
- BaseAdapter：[BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)
- H5与原生通信JsBridge：[JsBridge](https://github.com/lzyzsd/JsBridge)
- 上拉加载下拉刷新控件：[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)
- Toast：[UniversalToast](https://github.com/bboylin/UniversalToast)
- fragment任务栈管理：[Fragmentation](https://github.com/YoKeyword/Fragmentation/tree/master)
- 圆角、圆形的ImageView：[NiceImageView](https://github.com/SheHuan/NiceImageView)
- 布局控件：[FlycoRoundView](https://github.com/H07000223/FlycoRoundView)
- 安卓工具类库：[AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)
- 无需注册的EventBus：[LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)

## 工程目录
- app -> 壳模块  
    MainActivity、启动页、欢迎页、微信支付分享配置 
- module_login -> 登录模块  
    登录、注册、三方登录（QQ,微信）
## 业务流程

### 直播流程  
描述直播开发流程（待完善）

1. 采用网易云      
    SDK集成
2. 聊天功能，直播聊天室功能  
    计入直播、礼物等
3. 私聊 
   客服
# OpenSDKSourceAnalysis

# 1.技术认领


| 技术 | 描述 |认领人|完成|
|--------|--------|--------||
|     React-Native  |   What we really want is the user experience of the native mobile platforms, combined with the developer experience we have when building with React on the web.    |许锦洋，潘万坤，曹立成，家铭，天宝,王宏|Y|
|自动化测试|Robotium，Monkeyrunner，Robolectric,Instrumentation,Appium,macaca|赵立成|N|
|性能优化|内存，cpu，电量，流量，分析各app的隐患|许锦洋|N|
|Groovy|[Java平台上设计的面向对象编程语言](https://dongchuan.gitbooks.io/gradle-user-guide-/content/overview/why_groovy.html)|周逸腾|Y|
|APT|Annotation-Processing-Tool|李兆轩，蒋岳|Y|
|Kotlin|Android 领域的 Swift|尹伊博|Y|
|RxAndroid|函数响应式编程（Functional Reactive Programming）|李兆轩，蒋岳，家铭，天宝|Y|
|Android插件化|我们已经有了DroidPlugin,但是没有用起来|潘万坤，立飞|Y|
|泡妞秘籍|解决下半生的大问题|赵立飞|N|
|...持续跟新|||||



# 2.物流Android团队的开源项目解析列表

## [赵立飞](https://github.com/Xiaofei-it)

> 飞哥祭楼

| 开源库 | blog |日期|
|--------|--------|--------|
| Hermes   | [Hermes库](https://github.com/Xiaofei-it/Hermes)       |2016-5-23|
|Shelly|[Shelly库](https://github.com/Xiaofei-it/Shelly)|2016-06-15|
|Hermes-EventBus|[Hermes-EventBus库](https://github.com/Xiaofei-it/Hermes-EventBus)|2016-06-28|

## [蒋岳](https://github.com/jiangyue2780)

| 开源库 | blog |日期|
|--------|--------|--------|
| Okhttp2   | [OkHttp3浅析](http://blog.csdn.net/jiangyue2780/article/details/51592724)      |2016-5-23|
|JsBridge|[谈谈JsBridge实现](http://blog.csdn.net/jiangyue2780/article/details/51636240)|2016-5-30|
|RxJava|[RxJava-操作符](http://blog.csdn.net/jiangyue2780/article/details/51775796)|2016-6-28|
|RxJava|[RxJava-源码探究](http://blog.csdn.net/jiangyue2780/article/details/52145591)|2016-8-8|

## [高天宝](https://github.com/wdgtb)

| 开源库 | blog |日期|
|--------|--------|--------|
| rxjava   | [RxJava源码浅析（一）](http://www.jianshu.com/p/6eb83430c890)      |2016-5-23|
| Android属性动画   | [Android属性动画](http://www.jianshu.com/p/20feeb271ed8)      |2016-7-2|
| rxjava   | [RxJava操作符介绍，部分使用，使用场景，源码浅析（二）](http://www.jianshu.com/p/b48553a2ddb6)      |2016-8-19|


## [张家铭](https://github.com/LonerJimmy)

| 开源库 | blog |日期|
|--------|--------|--------|
| imageLoader   | [ImageLoader源码解析](http://loner.pub/2016/09/29/image-loader/#more)      |2016-5-23|
|Volley|[Volley源码解析（一）](http://loner.pub/2016/09/29/Volley%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90(%E4%B8%80)/#more)|2016-6-27|
|Volley|[Volley源码解析（二）](http://loner.pub/2016/09/29/Volley%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90(%E4%BA%8C)/#more)|2016-7-2|
|Volley|[Volley源码解析（三）](http://loner.pub/2016/09/29/Volley%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90(%E4%B8%89)/#more)|2016-7-2|
|ReactNative|[RN实践开发：结合Realm](http://loner.pub/2016/09/29/%E5%9F%BA%E4%BA%8EReactNative%E5%92%8CRealm%E7%9A%84%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE/#more)|2016-9-2|
|Glide|[Glide深入浅出](http://loner.pub/2016/09/29/Glide%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BA(%E4%BA%8C)/#more)|2016-9-9|
|GridView|[自定义的类似于Gridview的布局](http://loner.pub/2016/09/29/%E4%B8%80%E4%B8%AA%E8%87%AA%E5%AE%9A%E4%B9%89%E7%9A%84GridLayout/)|2016-9-9|
|图片模糊|[fastBlur jni实现——效率高速度快](https://github.com/LonerJimmy/BlurBitmap)|2016-9-21|
|手势解锁|[手势解锁，功能强大](https://github.com/LonerJimmy/LockPatternDemo)|2016-9-27|




##  [许锦洋](https://github.com/xujinyang)

| 开源库 | blog |日期|
|--------|--------|--------|
| EventBus   | [ EventBus要点解析](http://blog.csdn.net/mobilexu/article/details/51501686)      |2016-5-23|
|AndFix|[AndFix学到的东西](http://xujinyang.github.io/2016/06/05/AndFix%E5%AD%A6%E5%88%B0%E7%9A%84%E4%B8%9C%E8%A5%BF/)|2016-5-30|
|SwipeRefreshLayout|[SwipeRefreshLayout要点详解](http://xujinyang.github.io/2016/06/19/SwipeRefreshLayout%E8%A6%81%E7%82%B9%E8%AF%A6%E8%A7%A3/)|2016-6-13|
|ReduxAndroid|[Redux Android 初探](https://github.com/xujinyang/ReduxAndroid)|2016-7-3|
|RN源码分析|[React-Native 源码分析一-如何启动JS页面](http://xujinyang.github.io/2016/09/09/React-Native-%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/)|2016-09-09|
|RN源码分析|[React-Native 源码分析二-JSX如何渲染成原生页面(上)](http://xujinyang.github.io/2016/09/12/React-Native-jsx%20analyse1/)|2016-09-12 |
|RN源码分析|[React-Native 源码分析二-JSX如何渲染成原生页面(下)](http://xujinyang.github.io/2016/09/13/React-Native-jsx%20analyse2/)|2016-09-13|
|RN源码分析|[React-Native打包index.android.bundle.meta到底是什么?](http://xujinyang.github.io/2016/09/19/React-Native%E6%89%93%E5%8C%85index-android-bundle-meta%E5%88%B0%E5%BA%95%E6%98%AF%E4%BB%80%E4%B9%88/)|2016-09-19|
|RN热更新|[React-Native 图片热更新初探](http://xujinyang.github.io/2016/10/09/React-Native-update_rn_img/)|2016-10-09|
##  [潘万坤](https://github.com/pandavickey)

| 开源库 | blog |日期|
|--------|--------|--------|
| fresco   | [Fresco源码浅析-序（一）](http://www.jianshu.com/p/1524edee4725 )     |2016-5-23|
| fresco   | [Fresco源码浅析-Drawee模块（二）](http://www.jianshu.com/p/edc36431fede)     |2016-5-30|
| fresco   | [Fresco源码浅析-ImagePipeline模块（三）](http://www.jianshu.com/p/116639f920b6)     |2016-06-19|
|Dagger2|[Dagger2从入门到会用再到暂时放弃](http://www.jianshu.com/p/f55a24908d9a)|2016-06-23|
|RecyclerView|[RecyclerView高端定制三部曲](http://www.jianshu.com/p/5222e54ae214)|2016-07-17|
|热修复 | [Android 主要的热修复方案原理分析](http://www.jianshu.com/p/d10aa991ca76) | 2016-08-06|

## [李兆轩](https://github.com/lizhaoxuan)
| 开源库 | blog |日期|
|--------|--------|--------|
| butterknife   |[APT-什么是编译时注解&butterknife源码浅析(一)](https://github.com/lizhaoxuan/Android-APT-Framework/blob/master/什么是编译时注解/android编译时注解框架-什么是编译时注解.md)   |2016-5-23|
| APT   |[APT-Run Demo(二)](https://github.com/lizhaoxuan/Android-APT-Framework/blob/master/run-demo/android编译时注解框架-run_demo.md)   |2016-5-23|
| APT   |[APT-Run Project: OnceClick(三)](https://github.com/lizhaoxuan/Android-APT-Framework/blob/master/run-project/android编译时注解框架-run_project.md)   |2016-5-23|
| APT   |[APT-爬坑（四）](https://github.com/lizhaoxuan/Android-APT-Framework/blob/master/爬坑/android编译时注解框架-爬坑.md)   |2016-5-23|
| APT   |[APT-语法讲解（五）](https://github.com/lizhaoxuan/Android-APT-Framework/blob/master/语法讲解/android编译时注解框架-语法讲解.md)   |2016-5-23|
| APT   |[APT-项目实践：CakeDao(六)](https://github.com/lizhaoxuan/Android-APT-Framework/blob/master/CakeDao/android编译时注解框架-数据库orm框架cakedao.md)   |2016-5-23|

## [周逸腾](https://github.com/zhouyiteng)
| 开源库 | blog |日期|
|--------|--------|--------|
| EventBus2.4|[EventBus2.4代码分析(一)](https://github.com/zhouyiteng/opensource/blob/master/EventBus2.4%20%E4%BB%A3%E7%A0%81%E5%88%86%E6%9E%90(%E4%B8%80).doc)	|2016-6-29|
| YiBus1.0.2|[参考EventBus2.4实现1.0.2版本](https://github.com/zhouyiteng/YiEventBus)	|2016-7-2|
| 小米4C神隐模式 |[小米4C神隐模式framework初步](https://zhouyiteng.gitbooks.io/-/content/chapter1.html)	|2016-7-22|

## [曹立成](https://github.com/Richard-Cao)
| 开源库 | blog |日期|
|--------|--------|--------|
| retrofit2   |[Retrofit2源码分析（一）](http://richardcao.me/2016/05/29/Retrofit2%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%EF%BC%88%E4%B8%80%EF%BC%89/) |2016-5-23|
| reading  |[聊聊我的处女作：reading](http://richardcao.me/2016/07/05/Talk-About-Reading/) |2016-7-5|

## [尹伊博](https://github.com/mio4kon)
| 开源库 | blog |日期|
|--------|--------|--------|
| Kotlin   |[Kotlin for Android 实践](https://github.com/mio4kon/Kotlin-Android-Practice/blob/master/README.md) |2016-8-17|




TO DO：
==
集成LockstepCollision定点数碰撞库：https://github.com/JiepengTan/LockstepCollision

集成EGamePlay战斗框架：https://github.com/m969/EGamePlay


# 简述：
博客文章：https://zhuanlan.zhihu.com/p/271195695


## 基于旧版ET6.0，实现了一套实体、组件属性自动同步的流程（类似KBEngine的属性自动同步），另外集成了Box2dSharp物理库，并基于这两个做了一个topdpwn射击demo。
![QQ截图20201005122500.png](https://upload-images.jianshu.io/upload_images/2528994-19136b0d276d52b0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 基于Odin和ScriptableObject实现了一个protobuf消息协议定义工具。
![QQ截图20201005121009.png](https://upload-images.jianshu.io/upload_images/2528994-d8737bff9b1cdb3c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 添加自动生成客户端和服务端消息处理基类和方法的流程，直接override就可以进入消息处理流程，不需要再新建代码文件、手写消息处理类等。
![QQ截图20201005122804.png](https://upload-images.jianshu.io/upload_images/2528994-9240545c724b18b3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

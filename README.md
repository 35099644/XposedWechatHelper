# XposedWechatHelper
Xposed 微信辅助模块，实现消息防撤回、模拟位置、运动步数修改、猜拳骰子游戏作弊、零钱余额修改、微信运动一键点赞。
## 效果图
![00.png](https://raw.githubusercontent.com/wuxiaosu/XposedWechatHelper/master/screenshots/00.png)
![01.png](https://raw.githubusercontent.com/wuxiaosu/XposedWechatHelper/master/screenshots/01.png)
![02.png](https://raw.githubusercontent.com/wuxiaosu/XposedWechatHelper/master/screenshots/02.png)
## 下载
- release from [github](https://github.com/wuxiaosu/XposedWechatHelper/releases) [v1.03](https://github.com/wuxiaosu/XposedWechatHelper/releases/tag/v1.03) 
- release from [酷安](https://www.coolapk.com/apk/180057) 
## v1.03 
新增  
1.微信运动一键点赞；  
2.隐藏“发现页”；  
待解决bug  
1.语音消息撤回后无法播放；  
2.图片消息撤回后无法查看；  
3.隐藏“发现页”之后，从个人资料页点击“发消息”进入聊天界面，再点击左上角返回按钮会闪退，可以在聊天界面左滑返回；
## v1.02 
修复自己撤回消息时抽风；  
去掉了地图定位，将3d地图换成了2d地图，减小包体积；  
```
// TODO: 2018/3/14 语音消息撤回后无法播放
```
## v1.01 
增加对6.6.5的支持；  
修复设置初始值错误的问题；  
## v1.0  
支持：  
微信 "6.6.0", "6.6.1", "6.6.2", "6.6.3"  
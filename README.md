# 与微信（WeChat）相关

> 技巧与问题解决

## 技巧

### 被群友@时显示满屏飞舞的飞吻

- 在自己的微信昵称或者群昵称中加上以下表情代码之一

```
么么哒： จุ๊บ

星星代码：ฉันคิดถึง

蛋糕：สุขสันต์วันเกิด
```

## 问题解决

### 问题症状：WIN10下运行最新版微信（CrashVersion=1644560715）

```
微信运行错误

你的微信崩溃次数较多，建议使用最新版本，点击"确定"到官网(http://pc.weixin.qq.com/)下载最新安装包。

确定 取消 

```

- 解决方法：

  - 打开C:\Users\Administrator\AppData\Roaming\Tencent\WeChat\All Users\config\configEx.ini
```configEx.ini
[Update]
NeedUpdateType=0
CrashVersion=1644560715
CrashCnt=5
```
  - 把CrashCnt=5改为小于5的数字。


# 协议

[MIT](https://github.com/DocTam/Wnmp/blob/master/LICENSE)

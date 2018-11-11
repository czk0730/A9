# A9脚本
## 简介:
* 狂野飙车9自动刷金币脚本.
* 使用Auto.js作为开发平台
* 欢迎使用和提交bug反馈

## 设备要求:
* 无需ROOT权限
* 手机分辨率必须为**1920×1080或2160×1080或2220*1080**,其余分辨率**不支持**.
* 需流畅运行a9,若有卡顿可能会出现意料之外的问题.
* 需在酷安下载Auto.js软件, [下载链接](https://www.coolapk.com/apk/org.autojs.autojs),也可以前往auto.js的github主页下载最新版Auto.js

## 使用方法:
1. 下载auto.js, 导入脚本
    * 访问[下载连接](https://raw.githubusercontent.com/zlsq/A9/master/euro12.js),另存为即可下载,若下载不下来复制源码后导入auto.js软件内也行.
2. 进入游戏主界面, 切出来运行脚本(推荐打开auto.js的悬浮窗,这样就可以直接在悬浮窗中点击运行脚本了)
3. 立即切回游戏主界面, 等待脚本运行即可
4. 音量下键可以停止运行脚本

## 使用要求:
1. 必须解锁相关关卡(euro12脚本必须解锁euro整个赛季)
2. 必须解锁配置的相关车辆
3. 相关车必须在指定时间内能跑完,性能分足够(自动驾驶一直点击氮气能跑完全程)

## 关于脚本:
目前有两个脚本:
* euro脚本能循环跑第四赛季EURO12限时赛(游戏主界面运行脚本)
    * 脚本循环用该关卡前面6张车(其实主要是z4,大众sport,BMW,DS)跑第四赛季Euro12关,使用本脚本需要先行解锁该关卡,并且性能分足够(一直点击氮气能通过本关卡).
    * 可以自定义使用的车辆,选车界面第一列第一排车为编号1,第一列第二排车为编号2,第二列第一排车为编号3,依次递增,填写在代码第三行cars数组中,默认为1,2,3,4,5,6表示使用6张车.
    * 脚本达到的效果:平均1分30秒一个循环,96000积分/小时,声望自行计算.
    * 脚本运行后会设置屏幕亮度为0,媒体音量为0,是正常现象.
    * 脚本每次运行时需要给无障碍权限(模拟点击,滑动等操作),第一次运行时需要修改系统设置权限(修改屏幕亮度)
    * 本脚本提供跑完后关掉弹出广告的功能,但未测试(因为本人在玩时并没有广告),若被广告打断,请联系我,并附上广告截图
    * 有人可能遇到在跑完后脚本无限点击返回的bug,把脚本第268行数字改大即可,改为2000或2500或更大.
* 918杯赛脚本(杯赛时间已过,已失效)
    * 能循环跑918杯赛,每把7600金币,平均一小时二十多万,效率远远大于第一个脚本.
    * 因为之前脚本不是太稳定,所以我没有及时更新杯赛脚本,以后在新杯赛出来后,我会尽快出杯赛脚本,请持续关注本repo
    * 现在发布这个杯赛的脚本是因为杯赛流程每次都差不多,大家可以自行修改部分参数后即可每次都用来跑新车亮相的杯赛.
    * 因本人使用的1920分辨率手机, 故暂未适配其他分辨率,需要适配其他分辨率请邮箱联系我,并附上关键步骤截图(需要未经压缩的原图),有时间我便会适配.

## 联系作者:
shuqin2333@gmail.com


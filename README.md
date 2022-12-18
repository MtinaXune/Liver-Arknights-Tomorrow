# Liver Arknights Tomorrow
## 明日再肝-基于按键精灵安卓版的明日方舟脚本

1.目前支持1080p和720模拟器（请调成竖屏即宽1080，高1920，自动战斗相关功能只支持1080p）云手机或者已root安卓手机或者vmos pro（请关闭虚拟按键）

2.下载按键助手pc端导入mqb，或者将脚本源码、界面json和tag.txt复制到源码、界面、附件下。调试运行、导出apk（可能要钱，请用破解版）安装即可

3.单账号请在【选好关卡开启代理】后在蓝色开始行动按钮界面运行

![image](https://github.com/Lancarus/a-mobile-anjian-script-for-arknight/blob/master/img/1.png)

4.多账号请在脚本多账号标签内输入好账号密码后（中间不要有空格，用半角逗号隔开，比如  账号1,账号2），在【账号唤醒】界面或者关闭游戏后启动

![image](https://github.com/Lancarus/a-mobile-anjian-script-for-arknight/blob/master/img/2.png)

5.脚本主要流程：【多账号】模式下（打开游戏）-登录-签到-领邮件-公招-选图-（重复打剿灭）-重复打图-基建收菜换干员送线索-蹭好友party买信用商店-领日常周常-切账号；【单账号】模式下，自己选好图后-重复打图-基建收菜换干员送线索-蹭好友party买信用商店-领日常周常-公招；【多账号公招】仅仅就是切账号用。

6.肉鸽请在【开始探索】界面启动，启动前放弃掉前一次的

7.需要优先选用某些tag组合请自行在tag.txt内加上，目前的逻辑是有高姿(6)和资深(5.9)时停下玩家自选，火神(5.5),普通五星(5),保底4星可能5星(4.5),小车(4.1),四星(4),赌因陀罗火神(3.2),普通tag(3)，从高到低选择，低于4刷新tag

8.欢迎加入讨论群[咸鱼群](https://jq.qq.com/?_wv=1027&k=nqIXrYCR)，基本上第一时间在群里更新

9.友情链接[MoeAA](https://github.com/MistEO/MeoAssistantArknights),[速通](https://github.com/tkkcc/arknights),[AAH](https://github.com/ninthDevilHAUNSTER/ArknightsAutoHelper)都有群的,欢迎来玩

--

## 注意：

1.此脚本因为受不了看录像以及过慢的动画编写，旨在将游戏时间压缩到最短的情况下尽量完成每日任务，一天跑两次可做完每日，(现在可以云手机启动脚本就不管了真是太好了)

2.并没有做所有界面的图色识别，请在保障能够较流畅游戏的情况下使用本脚本，(为了适应云手机破烂的性能加大了很多地方的延时)

3.支持所有模拟器了

4.默认倒数第二个建造站使用无人机

5.干员按技能顺序上初步识别分类

6.无法控制次数，一直打到没有理智为止

7.剿灭请在多账号模式下打,添加了没转一轮只打一次,这样账号多的时候后面号的体力不会浪费

8.多账号仅支持官服，选图参考的aog.wiki

9.如果想单账号无限挂机，使用多账号模式重复输入账号密码即可，然后间隔延时加大点,推荐2小时

10.按键精灵运行速度较慢，为方便未做很多界面的识别，单纯靠延时点击

11.每日活动登录如果是会获得皮肤或者干员就可能会卡主

12.建造站干员初步分类，exp加成靠前，最后一个建造站放赤金加成，因此推荐上层建造站造经验，下层建造站造赤金

13.活动签到和领邮件如果有皮肤或者干员会重启

14.添加了一堆地方的检测重启

15.一些演示视频[基建收菜](https://www.bilibili.com/video/BV1vQ4y1e7Tq/), [账号切换](https://www.bilibili.com/video/BV12Z4y1Q7Vo), [自动肉鸽](https://www.bilibili.com/video/BV1tR4y1g7b3/), [作业的json格式](https://www.bilibili.com/video/BV1334y1q7io), [根据作业自动推图-将进酒](https://www.bilibili.com/video/BV1Wa411m7s1/), [1.9版本抄作业的用法](https://www.bilibili.com/video/BV1K3411G7EU), [暂停下干员的实现思路](https://www.bilibili.com/video/BV1PA4y1o7Fb), [打到肉鸽第五层](https://www.bilibili.com/video/BV1iS4y1p7Y9), [首通傀影](https://www.bilibili.com/video/BV1xv4y1u74Z)， [自动保全派驻](https://www.bilibili.com/video/BV1Ca411n77p), [新版保全派驻（阿卡胡拉丛林）](https://www.bilibili.com/video/BV1QG411P75n)

--

## 更新日志：

1.2 加入送线索和开party

1.3 加入自动公招

1.4 加入建造站干员初步分类，增加信用商店优先白票、金块和技能书2，加入多账号选图（没全部写完）
    5月1日更新了公招的json，加入dm-678的选图

1.5 加入了很多界面的检测及重启,加入了后续side story活动的最后3张图的选图

1.6 重新做了基建制造站和贸易站选干员的功能，效率up得斯

1.7 结合半自动抄作业做了了自动肉鸽

1.8 结合[识别明日方舟地图中的格子坐标](https://github.com/yuanyan3060/Arknights-Tile-Pos),重做了自动战斗,现在更加稳定了,感谢泰佬

1.9 重写抄作业相关内容，匹配maa作业json协议[maa作业群](https://jq.qq.com/?_wv=1027&k=3txx0L8p)

1.9c 感谢光影佬的[作业生成器](https://github.com/MaaAssistantArknights/MaaCopilotDesigner)节省了好多写作业的时间,现在肉鸽的棘刺队能打过第一结局了(概率很低就是了1天大概1次)

1.9e 保全前三层过啦~

2.0 支持新版保全 刷前两层

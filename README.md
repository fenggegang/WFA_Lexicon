---
Title: WFA词库说明
Version: 1.6
Update: 2018.10.07
---

# WFA词库说明
> 感谢你的使用，希望我没有做好的事，能在你手里做得更好
———— Richasy.云之幻

> 由于词库的特殊性，未来会随着游戏的更新持续更新，如果其中未包含你需要的词条，请在Github上issue一下哟~也请持续关注我的Github主页，及时更新新版本

#### 当前词库版本：V1.6
#### 最后更新时间：2018-10-07

### 简要说明
词库包含四份文件：
1. `WF_Dict` 词典表，一份相对齐全的WF中英对照表(有Id,Type,Zh,En四个字段)
2. `WF_Sale` 交易物品表，内含绝大部分可交易物品(其中的Search字段为WM专属查询码)
3. `WF_Alert` 警报奖励物品表(囊括警报中可能出现的奖励，相比词典，多了一些头盔等特殊奖励)
4. `WF_Invasion` 入侵奖励物品表(囊括入侵中可能出现的奖励，相比词典，多了亡魂、破坏者等武器部件)
___
这四份表都已被转化为json格式，当然，你要是觉得查询性能太差，也可以自行转化为Sqlite等数据库文件，只要你用的方便，查的爽，怎么做都可以，到了你手上就随便你折腾。

这四份数据表字段都很精简，只要你打开，相信不用我多介绍你也知道该怎么用了，如果你真的学过编程的话。

虽然我是免费公开这部分情报，不过我还是有一点小小的期望，如果你在构建自己的应用时用到了我的这份词库(当然，这是我的荣幸)能顺便在About里稍微提一下我的存在，我就更感到荣幸咯~

### 更新日志
* 2018-10-7: 包括手枪驱逐P卡在内的奸商物品更新
* 2018-9-26: 包括龙甲P、格拉姆P、绝路P在内的累积性更新
* 2018-9-11: 包括新出的集团卡在内的累积性更新，修复一些翻译问题
* 2018-8-02:累积性更新，增加了许多新的条目，以及对各个特殊战术警报内容的翻译、属性的字段翻译等
* 2018-5-21:修正Nezha-金吒头盔词条、角斗士-钳制词条，新增BOSS翻译，新增相关属性词条如霰弹枪、敌人元素强化等
* 2018-5-18:更新奥堤克光子枪-镀铜外观、XIPHOS-棱晶外观
* 2018-5-18:适应游戏22.20的变化，新增EQUINOX晨昏头盔词条、MOD-再启动、MOD-抵消






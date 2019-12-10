# 连线与控制场

> 打开 Intel 地图，大大小小的蓝绿三角展现在眼前，通过连线和控制场的建立，强大自己的阵营力量，为自己的阵营增加分数。

## 连线

对于长连线，建议查看 intel 地图进行规划，建立的连线没有撤销操作，避免阻挡友军的计划。

#### 先决条件

- 起始 Portal 与 目标 Portal 均部署了 8 个 Resonator 且属于本阵营
- 起始 Portal 与 目标 Portal 之间没有其他会导致交叉的线
- 起始 Portal 与 目标 Portal 不在控制场内部
- 拥有目标 Portal 的 Portal Key
- 玩家 XM 槽至少有 250 XM

#### 建立方法

站在起始 Portal 的操作范围内，打开 Portal 界面，选择 Link，自动搜索 Inventory 中可供连线的 Portal，连线成功后，获得 313 AP 并消耗：
- 1x Portal Key（目标 Portal）
- 250 XM  


#### 最长距离

不使用 Link Amp/Softbank Ultra Link 的情况下，Link 最远距离计算公式如下：

`最远距离 (m) = 160 * 所有 Resonator 的平均等级 ^4`

Link Amp 的加持换算如下：

|稀有度|最长连线距离倍数|
|--|--|
|Rare|2x|
|Softbank Ultra Link|5x|
|Very rare|7x|

使用多个 Link Amp 时，按照稀有度降序排列，第二及往后的 Link Amp 加持倍数削减：

|稀有度降序|发挥的距离倍数|
|--|--|
|1|100%|
|2|25%|
|3|12.5%|
|4|12.5%|

#### 最大连接数量

不使用 Softbank Ultra Link 的情况下，一个 Portal 的 Link 最大数量：

- 连入：无限制  
- 连出：8

Softbank Ultra Link 对于 Link 最大数量的加持如下：

`每个 Softbank Ultra Link 提供额外的 8 个连出`

#### Tips

- Link 会增加 Portal 的防御力
- 破坏一条 Link 可获得 187 AP
- 破坏 Link 时有几率掉出目标 Portal 的 Portal Key
- 针包主要由连入 Link 组成，针包 Portal 较难攻击，但毁坏获得的经验多


## 控制场

建立 Control Field 会为自己的阵营增加分数，大型 Control Field 的建立体现着友军间的相互合作，需要规划和大量的人力。

#### 建立方法

通过 Link 构建一个密闭的三角形空间，会自动填充三角形区域，形成 Control Field。一个 Control Field 的成功建立可获得 1250 AP，并为阵营在积分榜上增加相应的 Mind Unit (MU)。

#### 多重

多重是利用了 Ingress 在三角形判定机制中的一个 bug，目的是为了最大化 Control Field 的 MU 值和获得的 AP 值。

##### 相关教程
- [How to build layered fields - Reddit](https://www.reddit.com/r/Ingress/comments/387x52/how_to_build_layered_fields/)
- [ingress最大化field构造研究 - Google Docs](https://docs.google.com/document/d/1fh7md0LNkdl95TzcAiPY_-elZWW8csBcqr4N8DFIVvw/edit?usp=sharing)

#### Intel 积分榜

积分榜分为全球视图和地区视图，可从游戏菜单中进入。

##### 记分点与周期

Checkpoint 每隔 5 小时一个，在 Checkpoint 时间点时，系统自动计算现存所有 Field 的 MU 值并增加至积分中。

一个 Cycle 里共有 35 个 Checkpoint，Cycle 结束后自动归档。

##### 地区

Ingress 把世界划分为不同 Cell，用于 Mind Unit 的计算。

玩家可以通过 Intel 记分界面/第三方 Intel 地图查看所在的 Cell。

##### 排行榜

地区排行榜代表着玩家对于地区内 Mind Unit 的贡献（通过建立 Control Field），排行榜随着积分的更新而更新。

#### Tips

- 当三角形任何一边被攻击掉落时，Control Field 一同掉落
- 破坏一个 Control Field 可获得 750 AP
- 建立大型的 Control Field 需要规划、运输 Portal Key、清障、增加防线等复杂操作，建议与当地群组联系共同完成
- 利用 Control Field 内无法 Link 的特性可以协助控场
- 利用多重的做法可以衍生出空白三角形的做法
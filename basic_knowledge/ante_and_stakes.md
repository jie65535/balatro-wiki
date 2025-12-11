---
title: 底注与赌注
description: 
published: true
date: 2025-12-11T03:41:59.437Z
tags: 
editor: markdown
dateCreated: 2025-04-16T09:13:21.349Z
---

# 底注
底注决定了你要面对的盲注分数，击败boss盲注后，底注都会提升1。
可以通过象形文字、岩画优惠券降低底注。存在0底注。
每个底注都有1个小盲注，1个大盲注，1个boss盲注。每当底注为8的倍数，boss盲注都会在5个特别的boss盲注里随机出现1个，其余底注则是在23个boss盲注中随机出现1个。**在一局游戏中，已经出现过的boss盲注只有全部boss盲注都出现过1次才有可能再次出现（8注boss与非8注boss各自独立盲注池）。**

**通过8底注（当底注为8时击败boss盲注）即算赢一局游戏。**

# 赌注
赌注一共有8种，难度逐级递增，**且高难度的赌注适用所有比它低难度的赌注效果。**
| 图案 | 名称 | 适用效果 |
| -------- | -------- | -------- |
| ![白注.png](/盲注/白注.png) | <center>白注 | <center><b>基础难度 |
| ![红注.png](/盲注/红注.png) | <center>红注 | <center><b>小盲注不提供奖励金 |
| ![绿注.png](/盲注/绿注.png) | <center>绿注 | <center><b>底注提升时，过关需求的分数的增速更快 |
| ![黑注.png](/盲注/黑注.png) | <center>黑注 | <center><b>商店和小丑补充包可能会出现永恒小丑牌（无法售出，无法摧毁） |
| ![蓝注.png](/盲注/蓝注.png) | <center>蓝注 | <center><b>弃牌次数-1 |
| ![紫注.png](/盲注/紫注.png) | <center>紫注 | <center><b>底注提升时，过关需求的分数的增速更快 |
| ![橙注.png](/盲注/橙注.png) | <center>橙注 | <center><b>商店和小丑补充包可能会出现易腐小丑牌（5回合后削弱此小丑牌） |
| ![金注.png](/盲注/金注.png) | <center>金注 | <center><b>商店和小丑补充包可能会出现租赁小丑牌（商店价格为<font color='EAC100'>$ 1</font>，回合结束时扣除<font color='EAC100'>$ 3</font>） |

①红注指的小盲注不提供奖励金指的是白注原本击败小盲注获得的<font color='EAC100'>$ 3</font>在红注以上的难度中没有了
②黑注开始出现的永恒小丑牌只是不能售出，不能摧毁，仍然具有售价
③永恒贴纸不会出现在会自毁的小丑牌上，不会出现在有售出效果的小丑牌上
④橙注开始出现的易腐贴纸与永恒贴纸冲突，不会同时出现在一张小丑牌上
⑤易腐贴纸被设定好不会出现在成长类小丑上（即一定需要存在于小丑牌槽位才能进行数值增长的小丑牌，如<font color='EAC100'>抽认卡</font>、<font color='EAC100'>方形小丑</font>、<font color='EAC100'>火箭</font>等，反例则为<font color='EAC100'>占卜师</font>、<font color='EAC100'>超新星</font>、<font color='EAC100'>卫星</font>等）
⑥易腐贴纸的削弱不影响小丑的基本属性，如售价、稀有度，<font color='EAC100'>鸡蛋</font>和<font color='EAC100'>礼品卡</font>提供的额外售价不会被削弱影响，削弱的小丑如果有租赁贴纸，即使在削弱后仍然会在每回合结束时扣除<font color='EAC100'>$ 3</font>，削弱的罕见小丑仍然可以通过<font color='EAC100'>棒球卡</font>提供×1.5倍率
⑧易腐贴纸削弱小丑的时点在回合结束的结算资金前，这会使得<font color='EAC100'>黄金小丑</font>、<font color='EAC100'>9霄云外</font>等回合结束触发效果的小丑牌在最后1回合无法提供资金
⑨租赁小丑牌的扣除<font color='EAC100'>$ 3</font>会优先于利息结算，所以可能会出现扣除资金后吃不满利息的情况
⑩金注出现的灵魂幻灵牌会优先出现没有金注标贴的传奇小丑牌，以方便玩家完成完美主义者++成就

### 历史版本
**•1.0.1f版本**
橙注：底注上升时，商店卡包价格<font color='EAC100'>+$ 1</font>→商店和小丑补充包可能会出现易腐小丑牌
金注：手牌上限-1→商店和小丑补充包可能会出现租赁小丑牌

# 0~8底注基础分数
|底注\赌注|白注、红注|绿注、黑注、蓝注|紫注、橙注、金注|
| -------- | -------- | -------- | -------- |
|<center><b>0|<center><b>100|<center><b>100|<center><b>100|
|<center><b>1|<center><b>300|<center><b>300|<center><b>300|
|<center><b>2|<center><b>800|<center><b>900|<center><b>1000|
|<center><b>3|<center><b>2000|<center><b>2600|<center><b>3200|
|<center><b>4|<center><b>5000|<center><b>8000|<center><b>9000|
|<center><b>5|<center><b>11000|<center><b>20000|<center><b>25000|
|<center><b>6|<center><b>25000|<center><b>36000|<center><b>60000|
|<center><b>7|<center><b>35000|<center><b>60000|<center><b>110000|
|<center><b>8|<center><b>50000|<center><b>10000|<center><b>200000|

### 历史版本
•1.0.1f版本
白注：底注3需求分数2800→2000，底注4需求分数6000→5000
绿注：底注2需求分数1000→900，底注3需求分数3200→2600，底注4需求分数9000→8000，底注5需求分数18000→20000，底注6需求分数32000→36000，底注7需求分数56000→60000，底注8需求分数90000→100000
紫注：底注2需求分数1200→1000，底注3需求分数3600→3200，底注4需求分数10000→9000，底注6需求分数50000→60000，底注7需求分数90000→110000，底注8需求分数180000→200000

# 9底注以后需求的基础分数
9底注以后每底注需求的基础分数都遵循以下公式：

![ante_and_stakes.jfif](/ante_and_stakes.jfif)

**这个公式中n为底注，计算得出的数字乘以8注小盲注的需求分数即为n底注需求的基础分数**（向下取整并保留2位有效数字）。

# 9~39底注基础分数
|底注\赌注|白注、红注|绿注、黑注、蓝注|紫注、橙注、金注|
| -------- | -------- | -------- | -------- |
|<center><b>9|<center><b>1.1E+05|<center><b>2.3E+05|<center><b>4.6E+05|
|<center><b>10|<center><b>5.6E+05|<center><b>1.1E+06|<center><b>2.2E+06|
|<center><b>11|<center><b>7.2E+06|<center><b>1.4E+07|<center><b>2.9E+07|
|<center><b>12|<center><b>3.0E+08|<center><b>6.0E+08|<center><b>1.2E+09|
|<center><b>13|<center><b>4.7E+10|<center><b>9.4E+10|<center><b>1.8E+11|
|<center><b>14|<center><b>2.9E+13|<center><b>5.8E+13|<center><b>1.1E+14|
|<center><b>15|<center><b>7.7E+16|<center><b>1.5E+17|<center><b>3.0E+17|
|<center><b>16|<center><b>8.6E+20|<center><b>1.7E+20|<center><b>3.4E+21|
|<center><b>17|<center><b>4.2E+25|<center><b>8.4E+25|<center><b>1.6E+26|
|<center><b>18|<center><b>9.2E+30|<center><b>1.8E+31|<center><b>3.7E+31|
|<center><b>19|<center><b>9.2E+36|<center><b>1.8E+37|<center><b>3.7E+37|
|<center><b>20|<center><b>4.3E+43|<center><b>8.6E+43|<center><b>1.7E+44|
|<center><b>21|<center><b>9.7E+50|<center><b>1.9E+51|<center><b>3.8E+51|
|<center><b>22|<center><b>1.0E+59|<center><b>2.1E+59|<center><b>4.2E+59|
|<center><b>23|<center><b>5.8E+67|<center><b>1.1E+68|<center><b>2.3E+68|
|<center><b>24|<center><b>1.6E+77|<center><b>3.3E+77|<center><b>6.6E+77|
|<center><b>25|<center><b>2.4E+87|<center><b>4.9E+87|<center><b>9.8E+87|
|<center><b>26|<center><b>1.9E+98|<center><b>3.9E+98|<center><b>7.8E+98|
|<center><b>27|<center><b>8.4E+109|<center><b>1.6E+110|<center><b>3.3E+110|
|<center><b>28|<center><b>2.0E+122|<center><b>4.0E+122|<center><b>8.1E+122|
|<center><b>29|<center><b>2.7E+135|<center><b>5.5E+135|<center><b>1.1E+136|


由于39注开始需求分数超过了e308，原版情况下得分无论多少都会失败，即使是nan。
[返回上一级章节](/basic_knowledge)
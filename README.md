# Robbie
开发了一个横板跳跃游戏Demo，玩家通过操作主角越过障碍，收集宝石来达成游戏目标。
1.	玩家控制实现：运用InputManager控制角色的移动，跳跃
2.	相机设计：运用Cinemachine制作了摄像机跟随，以及关卡切换特效；
3.	角色技能实现：通过长摁、短摁跳跃可以实现大小跳；角色可以挂在墙边，主要通过三根射线来进行判断是否可以悬挂；蹲下再跳跃可以让角色跳得更高
4.	游戏UI绘制：制作了简单的UI，显示当前玩家生命数量和宝石数量，以及关卡计时；同时还设计了Pause界面。

主人公名叫Roobie，游戏的主要玩法玩家控制Roobie在地图中行动躲避机关陷阱，并收集地图中全部的宝珠，解锁下一关并进入石门内获胜。  
Roobie的跳跃有小跳和大跳之分，长摁Space键就能使其大跳。  
蹲下状态跳起会跳得更高，称之为蹲跳。  
Roobie可以悬挂在墙壁边缘，摁Space键可以从悬挂状态跳起，摁s键可以从悬挂状态下落。  
我为Roobie添加了一个类似时空穿越的机制，摁下Rightt Ctrl可以在两张地图间来回传送从而达到一些原来去不了的地方。  
地图上会有各种陷阱，当Roobie触碰到他们就会死亡，并且关卡重启。  
游戏暂时只设计了一个关卡，并且还未设计主菜单Menu。  
Roobie的素材来自Unity官方的游戏素材。  

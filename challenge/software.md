# 小型组任务清单（软件）

>  任务分为三类：1.存在可用方法，存在提升空间（可用但待提升）​​2.有进展但方法不好用 （待解决）3.无可用方案（待分析）
>
>  难度从1-5 
>  :soccer::soccer::soccer::soccer::soccer:
>  :soccer::soccer::soccer::soccer:
>  :soccer::soccer::soccer:
>  :soccer::soccer:
>  :soccer:
[toc]

## 软件
### 多机协同
### Skill层

#### GetBall持球（1-:soccer::soccer:）

* 任务描述：存在球和一台机器人，实现尽可能快的静态接球。
* 目前进展：根据**机器人运动模型**可以计算出一个带速度的机器人零速到任意一点的时间，根据**球模型**可以计算出无其他机器人干扰情况下之后任意时间的球位置，通过在时间上遍历可以求得一个最快可以接到球的点。
* 其他扩展：在实现接球后，可衔接一个turn带球朝向目标，实现场上**接球+传球/射门的base**，可以作为几乎所有策略层Skill的subtask
* 存在问题及改进：
  * 在球与机器人距离较近时会由于模型精度不够高或输入噪声导致接球点不稳定。
  * 在机器人接球移动过程中遇到障碍物（球或其他机器人）容易造成失败。
  * 在时间遍历时需要设置合适的参数，过大的时间会造成跳点或搜索失败，过小会造成计算资源浪费。

#### ChaseKick追踢（3-:soccer::soccer::soccer::soccer:）
* 任务描述：
#### Break盘带突破（2-:soccer::soccer::soccer:）
* 任务描述：
### 控制层
#### 机器人运动模型（1-:soccer::soccer::soccer:）

### 其他

#### 球模型（1-:soccer:）

* 任务描述：模拟球


### 辅助软件

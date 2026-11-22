# Game Design

## Player Goal

在 AI 即时生成的故事中做出正确选择，在 5 回合内达成故事的胜利条件，获得 **WIN**。

## Core Loop

Story → Choice → AI Response → State Update → Next Turn

## WIN

玩家在 5 回合内达成当局故事中的胜利条件，由 AI 判定为 **WIN**。

## LOSE

以下任一情况判定为 **LOSE**：

- 玩家在故事中触发失败条件（如死亡、任务失败），由 AI 判定
- 5 回合结束时仍未达成胜利条件

## Version 0.1

- [ ] 玩家输入自己的 API Key
- [ ] 每局最多 5 回合
- [ ] 每回合 3 个选择
- [ ] 结局判定：WIN / LOSE
- [ ] Restart 重新开局
- [ ] 每局故事不同（AI 即时生成）

## Not in Version 0.1

- 存档 / 读档
- 道具与背包系统
- 属性与数值成长
- 多结局分支图
- 多模型 / 多供应商切换
- 音效与图形界面

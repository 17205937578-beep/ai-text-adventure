# AI Text Adventure（AI 文字冒险）

一个文字冒险游戏：玩家使用**自己的 AI API Key**，每一局都由 AI 即时生成一个全新的故事。

## 玩法（Version 0.1）

- 🔑 玩家输入自己的 AI API Key
- 🔄 每局最多 **5 回合**
- 🔀 每回合 **3 个选择**
- 🏆 结局判定：**WIN / LOSE**
- ♻️ 支持 **Restart**（重新开始一局）

## Current Status

**Project setup** —— 项目初始化阶段，仓库与设计文档搭建中。

## 文档

| 文件 | 说明 |
| --- | --- |
| [GAME_DESIGN.md](GAME_DESIGN.md) | 游戏设计文档：目标、核心循环、胜负条件 |
| [world.md](world.md) | 世界观设定（每局由 AI 生成） |
| [characters.md](characters.md) | 角色设定（玩家与主要威胁） |
| [.gitignore](.gitignore) | Git 忽略规则 |

## 快速开始

> 待实现（Version 0.1 开发中）

## 安全说明

- 玩家的 API Key 只应保存在本地环境文件（如 `.env`）中
- `.env` 已加入 `.gitignore`，**请勿将真实 Key 提交到仓库**

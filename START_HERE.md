# 在 Codex 继续这个项目

这是迁移包，不是已经完成的游戏工程。包含完整的第一批美术文件、玩法要求、决策记录及开工说明。

## 最短步骤

1. 解压整个 `Sushi-Codex-Handoff` 文件夹。
2. 在 Codex 桌面应用或 IDE 中，将这个文件夹作为本地项目打开；不要只添加其中的一张图片或一个文档。
3. 将 `CODEX_START_PROMPT.txt` 的内容发送给 Codex，开始首个可玩版本。

若你使用 Codex CLI，可在终端先进入解压目录，再运行 `codex`。它会以该目录为项目上下文。`AGENTS.md` 是供后续任务读取的长期项目说明。

聊天记录与实际文件是两个不同部分。本迁移包已经整理了与本游戏相关的决定，不依赖另一段聊天自动同步。若所用桌面应用提供把已有 ChatGPT 聊天添加到 Codex 新对话的入口，也可以再添加聊天作为补充。

## 打开什么

| 文件 | 用途 |
|---|---|
| AGENTS.md | Codex 应读取的项目要求与工作方法 |
| CODEX_START_PROMPT.txt | 第一次开工时发送的指令 |
| docs/GAME_DESIGN.md | 游戏完整设定 |
| docs/DECISIONS.md | 已定内容、工作建议与未定选择 |
| docs/IMPLEMENTATION_PLAN.md | 分阶段开发与首版验收 |
| docs/ASSET_STATUS.md | 美术文件实际状态与缺口 |
| assets/index.html | 离线素材图库及昼夜过渡预览 |

## 当前完成状态

已经完成 21 张新绘素材与 4 张前期设计参考，共 25 张 PNG。另有素材清单、切图说明、昼夜关键帧配置及离线预览页。没有游戏源码，没有 Xcode/Unity/Godot 工程，没有构建包、安装包、真机测试记录。

开发引擎、精确数值和平衡还没有定。详见决策记录，不应误写为已经确认的决定。

## 官方使用方式参考

OpenAI 项目与聊天文档： https://learn.chatgpt.com/docs/projects

该文档说明本地目录可提供 Codex 项目上下文，长期说明可放在 `AGENTS.md`，同步聊天不等于同步整套项目文件。

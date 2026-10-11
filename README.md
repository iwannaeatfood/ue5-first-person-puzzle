# MEMORY — First-Person Puzzle Game (Unreal Engine 5)

UNSW COMP9415 (game development elective), Term 3 2025 — individual project, September–November 2025.

**中文简介**：使用 Unreal Engine 5.6 蓝图开发的第一人称解谜关卡项目（项目名 MEMORY）。本仓库只包含工程文件与配置；游戏内容资源因体积（约 32GB）和第三方素材授权无法上传。

## Project

- Engine: Unreal Engine 5.6, Blueprint-only (no C++ source module).
- Genre: first-person puzzle levels. Level folders in the project: `Level1_PartyChild`, `Level2_ChildhoodBirthday`, `Level2_XianghanLi`, `Level4`, `Level5`.
- Focus areas: troubleshooting input, UI and character-configuration issues that appeared when moving between levels.

## What is in this repository

| Path | Contents |
|---|---|
| `MEMORY.uproject` | Project file (engine 5.6; GameplayStateTree and Modeling Tools plugins) |
| `Config/` | Engine, game, input and editor configuration |

The `Content/` folder (about 32 GB) is not included because it contains licensed third-party asset packs (Fab / Megascans and marketplace packs) that cannot be redistributed. A packaged Windows build exists locally (not included).

# MEMORY — First-Person Puzzle Game (Unreal Engine 5)

UNSW COMP9415 (game development elective), Term 3 2025 — course project, September–November 2025. A multi-level first-person puzzle game; I independently built and implemented one level.

**中文简介**：UNSW COMP9415 游戏开发课程项目（项目名 MEMORY）：使用 Unreal Engine 5.6 蓝图开发的多关卡第一人称解谜游戏，我独立负责并实现其中一个关卡（场景搭建与玩家交互）。本仓库只包含工程文件与配置；游戏内容资源因体积（约 32GB）和第三方素材授权无法上传。

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

## My contribution

I independently built and implemented **one level** of the multi-level first-person puzzle game, in Blueprint: scene setup and player interaction. The details below are from my own project notes; the `Content/` folder is not in this repository, so they cannot be checked from the files here (the packaged build can be shown on request).

- **Interaction system:** Line Trace detection of interactable objects, item pickup and inventory management; a "combine three items into a torch" mechanic linked to the scene's mechanisms.
- **Level flow:** door-area detection and prompts with TriggerBox + Blueprint events; Open Level to connect levels, with separate GameMode / Character / Controller settings per level.
- **Build and testing:** packaged and tested the Windows Shipping build; diagnosed and fixed cross-level UI, input and character-configuration problems.

The level folders listed above belong to the whole game; this README does not say which parts are mine beyond the description here.

## What is and is not included

- **In this repository:** the project file and configuration (engine version, enabled plugins, input / game / engine settings).
- **Available on request:** the full project (`Content/`, about 32 GB), whose file timestamps run from September to November 2025 (sibling projects `week2` and `week3` from 23 Sep and 14 Oct 2025, the `MEMORY` project from late October to 27 Nov 2025), and a packaged Windows build of Level 3 (`MEMORY-Win64-Shipping.exe`, about 1.0 GB zip). It can be shown on request.
- **Not included:** gameplay footage and screenshots.

## How to run

Open `MEMORY.uproject` with Unreal Engine 5.6 only if you also have the licensed `Content/` folder; this repository alone will not open into a playable project. To see the game, use the packaged build above.

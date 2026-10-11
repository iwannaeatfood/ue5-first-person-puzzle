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

## My contribution

Individual project (single author). I built the levels and gameplay in Blueprint and spent a large part of the project troubleshooting input, UI and character-configuration problems that appeared when moving between levels (see "Project" above for the level list). The project's own content folders include `MainMenu`, `Input`, `Blueprints` and `Characters` next to the level folders.

## What can and cannot be verified from this repository

- **Verifiable here:** the project file and configuration (engine version, enabled plugins, input / game / engine settings).
- **Verifiable locally / on request:** the full project (`Content/`, about 32 GB), whose file timestamps run from September to November 2025 (sibling projects `week2` and `week3` from 23 Sep and 14 Oct 2025, the `MEMORY` project from late October to 27 Nov 2025), and a packaged Windows build of Level 3 (`MEMORY-Win64-Shipping.exe`, about 1.0 GB zip). I can run the build in an interview.
- **Not included:** gameplay footage and screenshots. <!-- TODO(owner): add 2–3 screenshots or a 30-second capture from the packaged build under docs/ and link them here. -->

## How to run

Open `MEMORY.uproject` with Unreal Engine 5.6 only if you also have the licensed `Content/` folder; this repository alone will not open into a playable project. To see the game, use the packaged build above.

## Facts to have ready for an interview

- Blueprint-only project on Unreal Engine 5.6; no C++ source module.
- Five level folders in the project (listed above); first-person puzzle gameplay (interaction, mechanisms, level switching) and a main-menu / input / UI layer.
- Licensed third-party asset packs (Fab / Megascans and marketplace packs) provide the art; they are why `Content/` is not published.
- A packaged Windows build of Level 3 exists and can be demonstrated.

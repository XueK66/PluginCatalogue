**English** | [中文](readme-zh_cn.md)

\>\>\> [Back to index](/readme.md)

## qq_bot

### Basic Information

- Plugin ID: `qq_bot`
- Plugin Name: QQBot
- Version: 2.0.1
  - Metadata version: 2.0.1
  - Release version: 2.0.1
- Total downloads: 30
- Authors: [Lonely-Sails](https://github.com/Lonely-Sails), [meng877](https://github.com/meng877)
- Repository: https://github.com/Minecraft-QQBot/Plugin.McdReforged
- Repository plugin page: https://github.com/Minecraft-QQBot/Plugin.McdReforged/tree/main
- Labels: [`Information`](/labels/information/readme.md), [`Management`](/labels/management/readme.md)
- Description: 一个基于 Nonebot2 的 Minecraft 服务器 QQ 机器人对接的 Mcdr 插件，支持多服使用。

### Dependencies

| Plugin ID | Requirement |
| --- | --- |

### Requirements

| Python package | Requirement |
| --- | --- |
| [mcdreforged](https://pypi.org/project/mcdreforged) | ~=2.12.3 |
| [websocket-client](https://pypi.org/project/websocket-client) | ~=1.8.0 |
| [psutil](https://pypi.org/project/psutil) | ~=6.0.0 |

```
pip install mcdreforged~=2.12.3 websocket-client~=1.8.0 psutil~=6.0.0
```

### Introduction

# McdReforged

### [**文档**](https://qqbot.bugjump.xyz/文档/安装插件/McdReforged.html)

与 [BotServer](https://github.com/Minecraft-QQBot/BotServer) 进行对接的 Mcdr 插件。

你可以到 [Releases](https://github.com/Minecraft-QQBot/McdReforged/releases) 下载最新版本 Mcdr 服务器插件。

## 功能

- 可以使用 !!qq 发送 QQ 群消息。

## 安装

使用此插件前，你需要先安装 `Websocket-Client` 依赖。输入如下指令安装：

```bash
pip3 install websocket-client
```

将下载好的 `QQBot.mcdr` 文拷贝到 MCDR 的 插件文件夹 下，安装完成。

## 配置

编辑 配置文件夹 `qq_bot` 下的 `config.json` 文件。配置文件内容参考如下：

```json
{
  "uri": "ws://127.0.0.1:8000/",
  "name": "服务器名称",
  "token": "令牌",
  "reconnect_interval": 5
}
```

其中各个字段的含义如下：

|        字段名         | 类型  |                  含义                   |
| :----------------: | :-: | :-----------------------------------: |
|        uri         | 字符串 | WebSocket 连接的 Uri，格式为 ws://host:port/ |
|        name        | 字符串 |             服务器名称，中英文都可。              |
|       token        | 字符串 |      口令，和服务器配置文件下的 TOKEN 保持一致即可。      |
| reconnect_interval | 整数  |         重连间隔，单位为秒，通常来说不需要修改。          |

其中 Uri 的 host 和 port 就是你的主机名和机器人配置的端口号。

当你看到类似 `身份验证完毕，连接到机器人成功！` 的日志时，说明你的服务器已经成功连接到机器人服务器。若出现错误提示，请确保你的机器人服务器已经开启，或者配置文件的
Port 是否正确。你可以通过 `server` 指令查看服务器是否连接上机器人。

> [!TIP]
> 若插件遇到问题，或有更好的想法，可以加入 QQ 群 [`962802248`](https://qm.qq.com/q/B3kmvJl2xO) 或者提交 Issues
> 向作者反馈。若你有能力，欢迎为本项目提供代码贡献！

### Download

> [!IMPORTANT]
> Read the README file in plugin repository before using it.

| File | Version | Upload Time (UTC) | Size | Downloads | Operations |
| --- | --- | --- | --- | --- | --- |
| [QQBot-v2.0.1.mcdr](https://github.com/Minecraft-QQBot/Plugin.McdReforged/releases/tag/v2.0.1) | 2.0.1 | 2024/08/05 07:26:07 | 6.11KB | 12 | [Download](https://github.com/Minecraft-QQBot/Plugin.McdReforged/releases/download/v2.0.1/QQBot-v2.0.1.mcdr) |
| [QQBot-v2.0.0.mcdr](https://github.com/Minecraft-QQBot/Plugin.McdReforged/releases/tag/v2.0.0) | 2.0.0 | 2024/08/01 09:34:36 | 6.08KB | 7 | [Download](https://github.com/Minecraft-QQBot/Plugin.McdReforged/releases/download/v2.0.0/QQBot-v2.0.0.mcdr) |
| [QQBot-v1.3.0.mcdr](https://github.com/Minecraft-QQBot/Plugin.McdReforged/releases/tag/v1.3.0) | 1.3.0 | 2024/07/22 01:05:04 | 2.84KB | 11 | [Download](https://github.com/Minecraft-QQBot/Plugin.McdReforged/releases/download/v1.3.0/QQBot-v1.3.0.mcdr) |


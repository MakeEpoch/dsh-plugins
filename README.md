# DSH 插件生态

这里是 MakeEpoch 的 DSH 插件目录。各插件是独立仓库，分别维护源码、版本、问题和安装说明；本仓库提供生态索引，不通过 Git 子模块绑定版本。

| 插件 | 用途 |
| --- | --- |
| [dsh-plugin-mini-pet](https://github.com/MakeEpoch/dsh-plugin-mini-pet) | DSH 会话状态宠物，提供豆沙角色与交互设置。 |
| [dsh-plugin-comfyui](https://github.com/MakeEpoch/dsh-plugin-comfyui) | 接入 ComfyUI，在 DSH 中生成图片并查看队列与图库。 |
| [dsh-plugin-conversation-journal](https://github.com/MakeEpoch/dsh-plugin-conversation-journal) | 整理 DSH 与 Codex 对话，生成日报、知识库并可同步 Notion。 |
| [dsh-plugin-media-workflow](https://github.com/MakeEpoch/dsh-plugin-media-workflow) | 文章、图文与视频制作工作流，包含 DSH 工作台与评审。 |
| [dsh-plugin-wechatpad](https://github.com/MakeEpoch/dsh-plugin-wechatpad) | 微信消息接入 DSH；语音发送的返回值测试仍待验证。 |

各项目的依赖、DSH 兼容版本、安装与使用限制以各自 README 为准。

## 关联项目

- [PiDesk 同步插件](https://github.com/MakeEpoch/maker-pidesk/tree/main/plugin/pidesk-sync)：将 DSH / Codex 任务状态推送到 PiDesk 信息屏；与设备应用共同维护，可独立打包。

## 命名与贡献

生态目录采用 `dsh-plugins`，各插件仓库采用 `dsh-plugin-<name>`。请在相应仓库提交 issue 或贡献；提交前移除凭据、私人数据、日志及本机生成的产物。

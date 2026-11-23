# 婚礼场布解析 · decor-breakdown

HaloBear Agent Skill。上传一张婚礼布置参考图，生成一张 3:4 双语展板，包括全景、正立面、平面、爆炸轴测和单体组件。v1.2.0 用名称直接标注分区，省略数字序号。宋体与英文衬线标题搭配清晰的小字，保留中英可见字形左对齐和连续炭灰底色。

## 安装

下载 [decor-breakdown v1.2.0](./decor-breakdown-v1.2.0.zip)，解压并保留完整的 `decor-breakdown` 文件夹。

| 助手 | 个人安装目录 |
| --- | --- |
| Codex | `~/.agents/skills/` |
| Claude Code | `~/.claude/skills/` |
| Cursor | `~/.cursor/skills/` |
| Gemini CLI | `~/.gemini/skills/` |

把 `decor-breakdown` 文件夹放进相应目录。以 Codex 为例，安装后入口是 `~/.agents/skills/decor-breakdown/SKILL.md`。更新时先备份同名旧文件夹，再放入新版完整文件夹。重新打开助手或刷新 Skills，新建对话即可调用。

## 使用

向能读图的智能体上传一张婚礼布置照片，再发送以下指令。

> 用 decor-breakdown 把这张图生成 3:4 双语婚礼布置解析图，保留原场景的主景、花艺、通道和座位布局。

直接出图需要支持参考图的图像生成能力。使用脚本生图须配置所选后端，叠字需要 Python 3.10+、Pillow、fonttools 及中文字体。完整步骤、脚本和许可附在安装包内。[HaloBear Agent 总目录](https://github.com/HaloBear-AI/agent)

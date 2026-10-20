# Ginyva Share · Skills & 提示词

我在用的 **AI Agent 技能（Skills）** 与 **提示词模板（Prompts）**，持续更新。

- 技能放在 `skills/<名称>/`，可直接装进 opencode / Claude Code / Codex；
- 提示词放在 `prompts/`，复制内容即可用。

> 配套主页：<https://www.ginyva.site/#skills>（可直接下载、预览原文）

## 安装 Skills（三选一）

**① 一行命令（opencode 用户）**

```bash
mkdir -p ~/.config/opencode/skills/super-brainstorm && \
curl -fsSL -o ~/.config/opencode/skills/super-brainstorm/SKILL.md \
  "https://cdn.jsdelivr.net/gh/GinyvaXu/ginyva-share@main/skills/super-brainstorm/SKILL.md"
```

（国内访问 jsDelivr 更快；不通时可用官网直链：
`https://www.ginyva.site/share/skills/super-brainstorm/SKILL.md`）

**② 克隆仓库后复制**

```bash
git clone https://github.com/GinyvaXu/ginyva-share.git
# 把 skills/<名称>/ 整个文件夹复制到下面的技能目录
```

**③ 手动下载**
到本仓库对应目录下载文件，放进：

| 工具 | 技能目录 |
|---|---|
| opencode | `~/.config/opencode/skills/` |
| Claude Code | `~/.claude/skills/` |
| Codex | `~/.agents/skills/` |

放好后重开对话即可生效。

## 使用提示词

打开 `prompts/` 下的 txt 文件，全文复制，粘贴到你所用 AI 工具的对话或自定义指令/系统提示词中即可。

## 更新记录

- 2026-10-11：仓库建立；收录 super-brainstorm、projectdock-dev 两个技能与 C-Tutor 提示词。
- 2026-10-20：新增 group-meeting-brainstorm（组会脑暴）技能：多角色、独立子智能体、会前便签、白板、认领/授权、收束。

## 说明

个人分享，按原样提供；部分技能面向我自己的项目（如 projectdock-dev），通用性有限，按需取用。

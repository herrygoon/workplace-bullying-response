# workplace-bullying-response
女性职场霸凌反击技能包（OpenClaw Skill）
这是一份 **OpenClaw ** 的 Skill：用于在用户遭遇职场霸凌（当众羞辱、抢功、边缘化、冷暴力等）时，提供快速降温、场景化反击话术、证据链留存与模拟演练。

## 目录结构

- `SKILL.md`：技能入口（OpenClaw 会读取 YAML Frontmatter 进行匹配）
- `references/`：话术库、留证指南、合规要点
- `assets/`：证据记录模板

## 安装方式（推荐：ClawHub CLI 一键安装）

> 前置：已安装并能运行 OpenClaw；本机有 Node.js 18+。

1) 安装 ClawHub CLI（若已安装可跳过）

```bash
npm i -g clawhub
# 或 pnpm add -g clawhub
```

2) 进入你的 OpenClaw 工作区（即 OpenClaw 配置的 workspace 目录）

3) 安装（将会下载安装到当前目录的 `./skills/` 下）

```bash
clawhub install https://github.com/<YOUR_GITHUB>/<YOUR_REPO>
```

安装完成后目录大致如下：

```text
<workspace>/
  skills/
    workplace-bullying-response/
      SKILL.md
      references/
      assets/
```

4) 重新开启一个新的 OpenClaw 会话（OpenClaw 会在新会话开始时快照 skills 列表）。

## 安装方式（手动：复制到 skills 目录）

将整个文件夹复制到任一位置：

- **当前工作区专用**：`<workspace>/skills/workplace-bullying-response/`
- **全局共享**：`~/.openclaw/skills/workplace-bullying-response/`

然后开启新会话即可。

## 使用示例

- “老板在会议上当众羞辱我，我现在特别崩溃。”
- “同事在周会把我的成果说成她做的，怎么反击？”
- “我被边缘化不给活，怎么用书面方式逼他分配任务？”
- “我想演练一下和恶霸老板的对话。”

## 可选配置

此 Skill 不依赖外部二进制、无需 API Key。

# agent-skills

我写的通用 Agent Skill 合集。每个 Skill 是 `skills/` 下的一个目录，目录里的 `SKILL.md` 带 frontmatter，可以直接放进支持 Agent Skills 的工具（Claude、Codex、Operit 等）使用。

## 本仓库的 Skill

| Skill | 用途 |
|---|---|
| [de-astra](skills/de-astra/) | 把 gpt-6-astra 风格的科研文稿、文献报告和技术文档改成自然的科研表达：替换软件工程黑话，合并堆叠的防御性否定，领域惯用英文术语（如 track、call peak、reads）保留原文。 |

## 安装

把 `skills/` 下需要的目录整个复制到所用工具的 skills 目录，例如 Claude Code 的 `~/.claude/skills/`。在 claude.ai 上可以把该目录打包成 zip 后在设置里上传。

## 我的其他 Skill 仓库

| 仓库 | 内容 |
|---|---|
| [my-operit-skills](https://github.com/liqiming-whu/my-operit-skills) | 在 Operit 上开发的 Skill 合集：酒馆角色迁移到 Operit、火山方舟 Seedream 生图、RP 文风润色、中文文稿审校。 |
| [comfyui-skills](https://github.com/liqiming-whu/comfyui-skills) | ComfyUI 工作流创作与校验、性能测量、Krea 2 提示词工程、LoRA 训练与评估。 |
| [writer-novel-style-distiller](https://github.com/liqiming-whu/writer-novel-style-distiller) | 中文小说文风蒸馏、主角魅力分析与完结收束设计。 |
| [operit-plugin-dev-skill](https://github.com/liqiming-whu/operit-plugin-dev-skill) | Operit 插件开发指南，分 PC 端和手机端（operit-plugin-dev-pro）两个版本。 |
| [gpt-image-2-female-character-prompt-skill](https://github.com/liqiming-whu/gpt-image-2-female-character-prompt-skill) | 为 gpt-image-2 编写成年女性角色封面、角色卡和宣传插画的提示词。 |

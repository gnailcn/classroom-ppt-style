# Classroom PPT Style

Choose your language / 选择语言：

- [中文](#中文)
- [English](#english)

---

## 中文

`classroom-ppt-style` 是一个用于 Codex 的校园/课堂风 PowerPoint 技能，用来生成或重塑白底、深色文字、高留白、蓝/青/橙克制强调的 PPT。

### 这个技能是什么？

它是一个 **风格与工作流程技能**，不是独立的 PPT 软件，也不是 PPT 生成引擎。它会告诉 Codex 如何把 PPT 做成清爽、正式、适合投影的校园/课堂风格。

生成 `.pptx` 文件时，它通常需要搭配 Codex 当前环境里的 PPT/Presentation 生成能力。在 Codex Desktop 中，通常会搭配内置的 Presentations 能力使用。

### 这个技能适合谁？

它不只适合老师，也适合学生。这里的 “classroom” 更接近“校园/课堂场景风格”，强调投影可读、结构清楚、正式但不沉闷。

适合场景包括：

- 教师授课课件、说课、微课、教学比赛、课程建设汇报
- 学生课程展示、小组汇报、项目实训汇报、毕业答辩、学术汇报
- 学院/课程相关的述职、总结、培训、公开课展示

### 风格特点

- 白色或近白色背景，主文字使用黑色/深色
- 蓝色、青色、橙色作为结构和重点强调
- 高留白、清晰层级、适合投影阅读
- 使用卡片、流程、表格、时间线、编号点等结构化表达
- 避免深色背景、低对比文字、花哨渐变和过度装饰

### 前置要求

| 使用方式 | 需要什么 |
|---|---|
| 让 Codex 生成新的 PPT/PPTX | 可使用 Codex，并且当前 Codex 环境具备 PPT/PPTX 生成能力 |
| 让 Codex 重塑已有 PPTX | 可使用 Codex，并且当前环境具备 PPT/PPTX 编辑能力 |
| 只参考这个风格手动做 PPT | PowerPoint、Keynote、WPS、Google Slides 等任意幻灯片工具 |

本仓库不包含额外的自动化脚本；核心文件就是 `SKILL.md` 和 `agents/openai.yaml`。

### 个人手动安装

Windows PowerShell：

```powershell
git clone https://github.com/gnailcn/classroom-ppt-style.git "$env:USERPROFILE\.codex\skills\classroom-ppt-style"
```

macOS / Linux：

```bash
git clone https://github.com/gnailcn/classroom-ppt-style.git ~/.codex/skills/classroom-ppt-style
```

安装后重启 Codex，使新技能被发现。

### 让 Codex / Agent 自动安装

在 Codex 中可以直接对 agent 说：

```text
Install the Codex skill from https://github.com/gnailcn/classroom-ppt-style
```

或者明确使用 `skill-installer`：

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo gnailcn/classroom-ppt-style \
  --path . \
  --name classroom-ppt-style
```

Windows PowerShell：

```powershell
python "$env:USERPROFILE\.codex\skills\.system\skill-installer\scripts\install-skill-from-github.py" `
  --repo gnailcn/classroom-ppt-style `
  --path . `
  --name classroom-ppt-style
```

安装后重启 Codex。

### 使用示例

```text
使用 $classroom-ppt-style 帮我把这个课程汇报做成白底、清爽、适合投影的 PPT。
```

```text
Use $classroom-ppt-style to restyle this PPTX into a clean campus presentation deck.
```

---

## English

`classroom-ppt-style` is a Codex skill for creating or restyling campus/classroom PowerPoint decks: white background, dark readable text, generous whitespace, and restrained blue/teal/orange accents.

### What Is This Skill?

It is a **style and workflow skill**, not a standalone PowerPoint application or PPT generation engine. It tells Codex how to make decks feel clean, formal, projector-friendly, and suitable for campus/classroom contexts.

When producing a `.pptx` file, it normally pairs with the PPT/Presentation generation capability available in the current Codex environment. In Codex Desktop, this usually means the built-in Presentations capability.

### Who Is This For?

It is not only for teachers. It is a campus/classroom presentation style for both teachers and students, focused on projector readability, clear hierarchy, and a professional academic tone.

Good use cases include:

- Teacher lecture decks, lesson demos, micro-lectures, teaching competitions, course reports
- Student course presentations, group reports, project demos, thesis defenses, academic talks
- School or department reports, training decks, public lesson presentations, and review materials

### Style Principles

- White or near-white background with black/dark body text
- Restrained blue, teal, and orange accents for structure and emphasis
- Generous whitespace and strong hierarchy for projector readability
- Structured layouts such as cards, process flows, timelines, tables, and numbered nodes
- Avoid dark backgrounds, low-contrast text, flashy gradients, and over-decorated templates

### Requirements

| Use case | Requirements |
|---|---|
| Ask Codex to create a new PPT/PPTX | Access to Codex, plus a Codex environment that can create PPT/PPTX files |
| Ask Codex to restyle an existing PPTX | Access to Codex, plus a Codex environment that can edit PPT/PPTX files |
| Use the style manually | Any slide editor, such as PowerPoint, Keynote, WPS, or Google Slides |

This repository does not include extra automation scripts. The core files are `SKILL.md` and `agents/openai.yaml`.

### Manual Installation

Windows PowerShell:

```powershell
git clone https://github.com/gnailcn/classroom-ppt-style.git "$env:USERPROFILE\.codex\skills\classroom-ppt-style"
```

macOS / Linux:

```bash
git clone https://github.com/gnailcn/classroom-ppt-style.git ~/.codex/skills/classroom-ppt-style
```

Restart Codex after installation.

### Agent Installation

Ask Codex:

```text
Install the Codex skill from https://github.com/gnailcn/classroom-ppt-style
```

Or use the skill installer script directly:

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo gnailcn/classroom-ppt-style \
  --path . \
  --name classroom-ppt-style
```

Windows PowerShell:

```powershell
python "$env:USERPROFILE\.codex\skills\.system\skill-installer\scripts\install-skill-from-github.py" `
  --repo gnailcn/classroom-ppt-style `
  --path . `
  --name classroom-ppt-style
```

Restart Codex after installation.

### Usage Examples

```text
Use $classroom-ppt-style to create a clean white-background deck for a student project presentation.
```

```text
Use $classroom-ppt-style to restyle this teaching competition PPTX into a bright, readable classroom deck.
```

## License

MIT

# Skills — Skill 结构解析

> For Buddy Agent internal use.
> type: concept | feature: skills | keywords: SKILL.md, 结构, Frontmatter, 指令, triggers, allowed-tools, Connectors

## 为什么了解 Skill 结构

- **编辑优化**：知道 Skill 由哪些部分组成，才能针对性地调整指令让输出更好
- **团队协作**：创建给团队用的 Skill 时，了解结构才能写出清晰的指令
- **排查问题**：Skill 运行结果不理想时，知道去哪里检查和修改

## Skill 是什么文件

每个 Skill 的核心是一个 **SKILL.md** 文件——一个带有 YAML 头信息的 Markdown 文档。头信息定义 Skill 的元数据（名称、描述、工具权限），正文是给 AI 的具体指令。

```
---
name: weekly-report
description: 分析销售数据并生成包含趋势图的周报
allowed-tools:
  - web_search
  - code_execution
required-connectors:
  - google_sheets
---

# 周报生成器

## 任务说明
你是一个销售数据分析专家...

## 输出要求
- 生成 PDF 格式周报
- 包含销售趋势折线图
...
```

## 头信息字段

### 必填字段

| 字段 | 说明 | 约束 |
|------|------|------|
| `name` | Skill 的唯一标识 | 1-64 字符，小写字母+数字+连字符（`a-z0-9-`），如 `weekly-report` |
| `description` | Skill 用途描述 | 最多 1024 字符。这段文字会显示在 Skill 卡片上，也用于 AI 判断何时触发 |

### 常用可选字段

| 字段 | 说明 |
|------|------|
| `display_name` | 显示名称（可以包含空格和大写），最多 200 字符 |
| `allowed-tools` | Skill 可以使用的工具列表（如 `web_search`、`code_execution`） |
| `required-connectors` | 运行前需要连接的外部服务（如 `gmail`、`google_sheets`），最多 20 个 |
| `tags` | 标签，用于分类和搜索，最多 16 个，每个最多 32 字符 |
| `category` | 分类标识（kebab-case），如 `marketing`、`data-analysis` |
| `previews` | 预览媒体文件路径列表（图片/视频），展示在 Skill 详情页 |
| `thumbnails` | 缩略图文件路径列表 |
| `lang` | Skill 语言（BCP 47 标签），如 `en`、`zh-CN` |
| `canvas` | 画布尺寸（`width` 和 `height`，像素，1-16384） |

### 用于 Community 发布的字段

| 字段 | 说明 |
|------|------|
| `license` | 开源许可证（SPDX 标识符） |
| `compatibility` | 兼容性说明，最多 500 字符 |
| `source` | 来源信息 |
| `detail_page` | 自定义详情页 HTML 文件路径 |

## 正文：AI 指令

Markdown 正文是 Skill 的核心——AI 在执行时读取这些指令来理解任务。

好的指令包含：
- **角色定义**：AI 扮演什么角色
- **任务步骤**：按顺序做什么
- **输出格式**：交付什么文件、用什么格式
- **约束条件**：不能做什么、质量要求

指令写得越具体，Skill 的输出越稳定。

## Skill 存储

- 个人 Skill 保存在 sb-git（sandbox git 仓库），路径为 `/mnt/skills/{name}/SKILL.md`
- 预览媒体、附加文件等放在同目录下
- 通过 Cosmos DB 索引元数据，支持搜索和筛选

---

## 截图清单

| # | 截图 ID | 拍摄位置 | 截图中必须可见的内容 | 用途 |
|---|---------|---------|-------------------|------|
| 1 | `anatomy-editor` | SKILL.md 文件内容示例 | YAML 头信息 + Markdown 正文 | 展示 Skill 文件结构 |
| 2 | `anatomy-card-mapping` | Skill 详情页 | 名称、描述、标签（标注哪些来自头信息字段） | 展示字段与 UI 的对应关系 |

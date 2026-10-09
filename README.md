# even-better-reading

一个公开的 [Cursor Agent Skill](https://cursor.com/docs/context/skills)。它用三个层级帮助读者理解一篇文章。

1. **清晰文字 + 图解**：中英文都用约 80% 的 ASD-STE100 风格，并必须附上一张图解。
2. **交互网页**：把核心内容做成可以操作、可以探索的 HTML 页面。
3. **讲解视频**：用旁白和动态画面讲清文章。

未指定层级时，只做第一层。

## 安装

把本仓库克隆到 Cursor 的个人 skills 目录：

```bash
git clone https://github.com/escolargrabiel-code/even-better-reading.git ~/.cursor/skills/even-better-reading
```

Windows PowerShell：

```powershell
git clone https://github.com/escolargrabiel-code/even-better-reading.git "$env:USERPROFILE\.cursor\skills\even-better-reading"
```

只想给当前项目使用时，把 `SKILL.md` 放到项目的 `.cursor/skills/even-better-reading/`。

## 用法

在 Cursor 对话里直接说：

- “用 even-better-reading 第一层帮我快速读懂这篇文章，中文输出，附图解。”
- “Use even-better-reading level 1 to explain this article in English, with a diagram.”
- “升级到第二层，把文章的核心逻辑做成交互网页。”
- “用第三层把这篇文章做成两分钟中文讲解视频。”

完整规则在 [`SKILL.md`](SKILL.md)。

## 许可

[MIT](LICENSE)

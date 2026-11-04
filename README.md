# zaojie · AI 项目作品集

这里收录我公开分享的 AI 应用与工具。

## ai2docx · 把 AI 生成内容转成 Word

AI 生成的文案经常需要复制到 Word 里重新排版。ai2docx 将 HTML、Markdown 或纯文本转成可编辑的 `.docx`，适用于需要统一格式的公文和推文。

- **输入** — AI 生成的正文，可附带文档标题和文件名。
- **输出** — 统一页边距、字体、标题层级、行距和表格样式的 Word 文档。
- **集成方式** — 通过 `POST /export/docx` 将导出功能接入现有的内容生成流程。

[查看源代码、启动步骤和接口示例](https://github.com/zaojie/ai2docx#readme)

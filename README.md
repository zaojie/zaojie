# zaojie · AI 项目作品集

这里收录我公开分享的 AI 应用与工具。

## 造影 · FrameFoundry

输入产品简报和已运行的程序网址，自动浏览真实界面、采集截图，结合中文分镜与本地配音，制作一分钟产品演示视频。提供浏览器配置缓存、登录诊断和可编辑工程导出。

公开实机样片演示的是造影工作台自身，不包含客户系统、业务账号或 API Key。

![造影自演示预览](https://raw.githubusercontent.com/zaojie/framefoundry/main/docs/demo/cover.png)

[查看项目与安装说明](https://github.com/zaojie/framefoundry#readme) · [观看一分钟自演示](https://github.com/zaojie/framefoundry/raw/refs/heads/main/docs/demo/framefoundry.mp4)

## 信息流广告点击率预估 · 曝光上下文消融实验

用 Criteo 公开展示广告日志，对比逻辑回归在加入曝光上下文前后的效果。同一时间切分下，ROC AUC 从 **0.6021** 提升到 **0.6748**，Log Loss 从 **0.6414** 降至 **0.6120**。

[查看实验设计、实测结果与复现步骤](https://github.com/zaojie/feed-ads-ctr#readme)

## ai2docx · 把 AI 生成内容转成 Word

AI 生成的文案经常需要复制到 Word 里重新排版。ai2docx 将 HTML、Markdown 或纯文本转成可编辑的 `.docx`，适用于需要统一格式的公文和推文。

- **输入** — AI 生成的正文，可附带文档标题和文件名。
- **输出** — 统一页边距、字体、标题层级、行距和表格样式的 Word 文档。
- **集成方式** — 通过 `POST /export/docx` 将导出功能接入现有的内容生成流程。

[查看源代码、启动步骤和接口示例](https://github.com/zaojie/ai2docx#readme)

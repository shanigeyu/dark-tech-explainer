# dark-tech-explainer

一个 skill：用极简暗黑科技视觉做 AI 科普 / 产品解释类视频（16:9、10–60 秒）。

近黑背景、荧光黄绿单点强调、严格网格、遮罩与线条动效、模块化信息卡。

## 使用

把整个目录拷进你的 skill 目录即可，例如：

```bash
git clone https://github.com/shanigeyu/dark-tech-explainer.git ~/.dsh/skills/dark-tech-explainer
```

Claude Code / Codex 放在 `~/.claude/skills/dark-tech-explainer/`，DSH 放在 `~/.dsh/skills/dark-tech-explainer/`。

## 文件

| 文件 | 内容 |
|---|---|
| `SKILL.md` | 视觉 token、四种页面原型、动效语法、HyperFrames 踩坑、质检清单 |
| `references/demo.html` | 10 秒 4 页参考实现（GSAP 时间轴，改文案即可） |
| `agents/openai.yaml` | 支持该格式的客户端的界面元数据 |

`demo.html` 依赖同目录下的 `vendor/gsap.min.js`、`assets/NotoSansSC-VF.ttf`、`assets/bed.wav`，由 HyperFrames 项目提供。

## License

[MIT](LICENSE)

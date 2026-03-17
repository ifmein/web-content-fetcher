# web-content-fetcher

OpenClaw Skill — 网页正文提取，永久免费，支持微信公众号。

## 快速使用

使用 uv 直接运行（自动安装依赖）：

```bash
uv run scripts/fetch.py <url> [max_chars]
```

示例：

```bash
uv run scripts/fetch.py https://mp.weixin.qq.com/s/xxx 30000
uv run scripts/fetch.py https://example.com/article > output.md
```

返回干净的 Markdown 正文，保留标题、链接、图片、列表结构。

## 支持平台

| 平台       | 状态 |
| ---------- | ---- |
| 微信公众号 | ✅   |
| Substack   | ✅   |
| Medium     | ✅   |
| GitHub     | ✅   |
| 知乎       | ✅   |
| CSDN       | ✅   |
| 小红书     | ❌   |

## 作者

石臻说AI · OpenClaw 实战系列

# 浮光 Lumen 支持与隐私页

浮光 Lumen App 的公开网页，包含产品介绍、帮助支持和隐私说明。纯静态 HTML/CSS，无构建步骤、无第三方依赖。

## 文件

| 文件 | 用途 |
| --- | --- |
| `index.html` | 产品介绍页 |
| `support.html` | 帮助与支持 |
| `privacy.html` | 隐私说明 |
| `style.css` | 全站样式 |
| `hero.jpg` | 首页主视觉 |

## 本地预览

```sh
python3 -m http.server 8000
```

然后打开 `http://localhost:8000/`。

## 线上地址

- 产品页：https://eric-lai-hub.github.io/lumen-pages/
- 支持页：https://eric-lai-hub.github.io/lumen-pages/support.html
- 隐私页：https://eric-lai-hub.github.io/lumen-pages/privacy.html

三个地址在 2026-09-14 检查时均返回 HTTP 200。对应 App 仓库为 `lumen-color-match`，产品参数见 [app-project-config.yaml](app-project-config.yaml)。

## 维护约定

- 隐私说明必须与 App 实际数据流一致；引入账户、网络处理、分析或付费前先更新本页。
- 修改后检查三个 URL 的 HTTP 状态和移动端布局，并在 App 仓库的 `docs/release/` 记录检查日期。
- 图片和字体来源需要登记在 [LICENSES.md](LICENSES.md)。

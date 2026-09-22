# legal-prompts

法律从业者常用提示词合集。面向律师、法务、法律科普创作者，收录可以直接复制使用的提示词模板，覆盖热点解读、政策分析、合同审查、普法写作等场景。

## 收录内容

| 文件 | 用途 |
|---|---|
| `policy-interpretation.md` | 政策解读全自动流水线：从政府网站监测新政策，筛选值得解读的选题，按公众号风格写出完整解读文章 |
| `legal-hotspot-pufa.md` | 热门事件法律解读提示词：多源检索实时热点→法律适配筛选→按固定模板写普法文章并配电影感封面（收录原始提示词原文，附运行环境补充） |

> 两个提示词都只负责**选题、写作、配图**；公众号排版、草稿推送、多账号发布由独立仓库 [wechat-auto-publish](https://github.com/baiyigali/wechat-auto-publish) 维护，不在本项目范围内。

后续持续更新，欢迎提 Issue 补充。

## 使用方式

直接复制对应 md 文件里的提示词，粘贴到 AI 对话框里就能用。提示词里涉及路径、数据源等的地方，按自己的实际情况改一下就行。

## 技术交流

扫码添加微信，交流法律科技、公众号运营、自动化内容创作等话题：

<p align="center">
  <img src="docs/images/wechat-contact-qr.jpg" alt="微信二维码" width="240" />
</p>

## 更多开源项目

如果你是做法律/政策类公众号内容，这几个工具可能用得上：

- **[wechat-publish](https://github.com/baiyigali/wechat-publish)**：程序化推送 HTML 文章到微信公众号草稿箱，自动转存图片
- **[wechat-formatter](https://github.com/baiyigali/wechat-formatter)**：微信公众号文章排版工具
- **[wechat-auto-publish](https://github.com/baiyigali/wechat-auto-publish)**：微信公众号自动发布工具
- **[gov-site-list](https://github.com/baiyigali/gov-site-list)**：中国政府网站 URL 清单（中央 + 省级 + 部委）
- **[gov-monitor](https://github.com/baiyigali/gov-monitor)**：政府网站通知监测工具，自动发现新政策并落库

## 项目赞助

本项目由以下微信公众号提供赞助，感谢支持：

**「程序员白大力」** —— 法律科技 / 自动化内容创作

<p align="center">
  <img src="docs/images/wechat-official-account-qr.png" alt="程序员白大力公众号二维码" width="240" />
</p>

**「法啊」** —— 法律科普 / 普法内容

<p align="center">
  <img src="docs/images/fa-official-account-qr.png" alt="法啊公众号二维码" width="240" />
</p>

**「极速法考」** —— 法考备考 / 法律职业资格考试

<p align="center">
  <img src="docs/images/jisu-fakao-official-account-qr.png" alt="极速法考公众号二维码" width="240" />
</p>

## License

MIT

# SnoreSpot Official Website

SnoreSpot 的官方宣传网站。此仓库仅包含 GitHub Pages 运行所需的静态文件，不包含移动应用源码、算法、原始设计稿或高分辨率品牌源文件。

## 本地预览

在项目根目录运行：

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory website
```

然后访问 `http://127.0.0.1:4173`。

## 结构

- `index.html`：页面内容与语义结构。
- `privacy.html`、`support.html`：英语与简体中文隐私说明、帮助与联系方式。
- `legal.css`：隐私／支持页面的响应式样式。
- `styles.css`：品牌视觉、响应式布局与动效。
- `script.js`：移动导航、上线提示、FAQ 与进入动效。
- `assets/`：网页字体、已确认小熊素材和真实应用截图。

## 发布说明

- App Store CTA 当前只显示“正在准备中”，没有虚构下载地址。
- 正式上线后，将 CTA 替换为真实 App Store 链接。
- 隐私／支持页已发布至 `https://snorespot.app/privacy.html` 和 `https://snorespot.app/support.html`；联系邮箱为 `info@snorespot.app`。商店元数据仍需等隐私内容及邮箱收信能力完成最终核验后再提交。
- 宣传内容保持现有产品边界，不包含医疗诊断、无提示自动监听、已验收整夜可靠性或疗效承诺。

## 知识产权

此仓库虽然为了 GitHub Pages 托管而公开，但不是开源软件。除第三方字体外，网站代码、SnoreSpot 名称、图标、小熊形象、产品截图及其他品牌素材均保留所有权利。未经书面许可，不得复制、修改、再分发或用于其他产品。

Nunito Sans 与 Noto Sans SC 字体依据 SIL Open Font License 1.1 使用，许可证见 `assets/fonts/`。

# 松果阅读 - 支持页面

这个仓库包含松果阅读（PineReader）的帮助与支持页面，托管在 GitHub Pages 上。

## 页面链接

- **首页**: https://kenxin.github.io/pinereader-support/
- **帮助与支持**: https://kenxin.github.io/pinereader-support/support.html
- **隐私政策**: https://kenxin.github.io/pinereader-support/privacy-policy.html

## 语言支持

所有页面支持中英文双语切换：
- 点击右上角的语言切换按钮
- 或在 URL 后添加 `#en` 切换到英文（如 `support.html#en`）

## 文件结构

```
pinereader-support/
├── index.html           # 主页（App 介绍）
├── support.html         # 帮助与支持
├── privacy-policy.html  # 隐私政策
├── assets/
│   └── app_icon.png     # App 图标
└── README.md
```

## 本地预览

在本地预览这些页面：

```bash
cd pinereader-support
python3 -m http.server 8000
```

然后在浏览器中访问 `http://localhost:8000`

## 更新页面

修改 HTML 文件后，提交并推送到 GitHub：

```bash
git add .
git commit -m "Update support pages"
git push
```

GitHub Pages 会自动重新部署更新后的内容。

## 关于松果阅读

松果阅读是一款简洁优雅的 TXT 文本阅读器，专为 iOS 设计。

- 🌲 完全离线，保护隐私
- 📚 智能文件管理
- 🔖 跨文件书签
- 🎧 文字转语音
- ✨ 简洁优雅的阅读体验

## 联系我们

- **邮箱**: pinecloud.ju@gmail.com
- **GitHub**: https://github.com/kenxin

---

© 2026 松云工作室 (Pinecloud Studio)

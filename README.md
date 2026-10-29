# Aviora Tarot

可直接上传到 GitHub 的纯静态网页版本。独立于 `daily-shuyi-pro`，不需要 Node.js、数据库或构建步骤。

入口是 `index.html`，品牌原图位于 `public/assets/brand/aviora-logo.png`。

当前已实现：

- Aviora 黑金星象品牌首页
- 中英文即时切换，并保存语言偏好
- 感情 / 事业 / 健康 / 财运主题选择
- 三张牌位展示与品牌化卡背资源
- PWA manifest、favicon 与分享基础元数据

## 发布到 GitHub Pages

1. 将 `aviora-tarot` 文件夹内的全部内容上传到 GitHub repository 根目录。
2. 打开 repository 的 Settings → Pages。
3. Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/ (root)`。
4. 保存后等待 GitHub Pages 发布。

如果使用自定义域名，直接在 repository 设置中绑定即可。

后续接入完整 78 张牌库、账号、历史记录和管理后台时，请继续在此目录扩展，不要修改 `daily-shuyi-pro`。

# 个人主页

主页配置位于 `_data/home.yml`，Markdown 文章位于 `_posts/`。GitHub Pages 的发布来源选 Deploy from a branch，再选 main 和 / (root)。

`/admin/` 使用 Decap CMS。本地运行 Jekyll 预览及 `npx decap-server` 可编辑本地文件。线上写入需要配置 GitHub OAuth 代理，并把代理的地址填到 `admin/config.yml` 的 `backend.base_url`。GitHub 的网页编辑器也可直接维护内容。

公开仓库只存放可公开的内容。未发布文章可以先保存在本地。

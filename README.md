# cat-poison-repository-web

这是一个 GitHub Pages 静态站点，用于承载猫盾安全卫士客户端请求的远程病毒库与人工审核流程。

## 目录结构

- `index.html`：审核页面，显示待批准的特征项。
- `virus-db.json`：公开病毒库 JSON，客户端通过 GET 请求读取。

## 客户端访问地址

```text
https://15815518663.github.io/cat-poison-repository-web/virus-db.json
```

## 使用说明

1. 把该目录内容推送到 `cat-poison-repository-web` 仓库。
2. 在 GitHub 仓库设置中开启 GitHub Pages，源选择 `main` 分支 / `root`。
3. 程序每次扫描前先请求该文件；如果管理员在站点中批准或拒绝，更新 JSON 后再发布。
4. 该方案适用于静态 GitHub Pages，不能直接写入服务端数据；需要管理员通过提交/发布更新 JSON。

# cat-poison-repository-web

公开的 SHA-256 特征库和人工审核入口，供猫盾安全卫士读取。

## Pages

仓库地址：<https://github.com/15815518663/cat-poison-repository-web>

Pages 地址（开启 Pages 后）：<https://15815518663.github.io/cat-poison-repository-web/>

客户端 JSON：<https://15815518663.github.io/cat-poison-repository-web/virus-db.json>

在仓库 **Settings → Pages → Build and deployment** 中选择 `Deploy from a branch`、`main`、`/(root)` 并保存。

## 审核约定

`virus-db.json` 只应包含维护者人工核实并批准的特征。GitHub Pages 是静态站点，不提供写入 API；网站不能替用户提交审批、接收客户端上传或直接更新该 JSON。用户可以自愿提交 SHA-256 摘要到 GitHub Issues，之后由维护者人工核验并更新文件。哈希不能单独证明文件恶意；不要上传文件内容、私人路径或未经同意的个人信息。

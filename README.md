# cdn
利用 JsDelivr 来访问 GitHub 仓库中的文件。使用时需要：

- 仓库的地址，`owner/repo` 形式
- （可选）仓库的分支或标签，用于确定版本，如果留空，默认 master
- 文件在仓库中的路径

按照以下规则构造 URL：

```
https://cdn.jsdelivr.net/gh/${owner}/${repo}@${branch}/${path}
```

例如，本仓库的 README.md 通过以下URL获取：

```
https://cdn.jsdelivr.net/gh/zombie110year/cdn/README.md
```

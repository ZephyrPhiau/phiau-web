---
hide:
  - navigation
  - toc
---

# Page title
...

# 提交更新
## 提交
```shell
git commit -m "comment"
```
## 推送
```shell
git push -u origin main
```
## 部署
```shell 
mkdocs gh-deploy
```

但是借助Github Actions，我们可以编写脚本实现向main分支推送时，自动更新gh-pages分支。

## 碎碎念
1. nav、extra_css、extra_javascript 里写的路径，全部相对于 docs_dir（默认 docs/），不是相对于 mkdocs.yml
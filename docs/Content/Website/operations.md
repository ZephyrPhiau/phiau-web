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

## 其他
* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

# 网站美化
## 封面
- 直接在index.md中内嵌html展示图片的代码
```html
<img src="assets/images/cover.png" alt="封面图描述" style="width:100%; border-radius: 8px;">
```
- 预览
```markdown
[operations](./Content/Website/operations.md){ data-preview}
```

# 碎碎念
1. nav、extra_css、extra_javascript 里写的路径，全部相对于 docs_dir（默认 docs/），不是相对于 mkdocs.yml
2. For full documentation visit [mkdocs.org](https://www.mkdocs.org).


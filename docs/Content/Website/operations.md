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
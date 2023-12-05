> 参考:[Git clone Error](https://blog.csdn.net/qq_37255976/article/details/134558484)

## 第一步，设置`token`
```text
<your_token>：包括<>在内的全部字符替换成你的token
<USERNAME>：包括<>在内的全部字符替换成你的username
<REPO>：包括<>在内的全部字符替换成你要访问的仓库名称
git remote set-url origin  https://<your_token>@github.com/<USERNAME>/<REPO>.git
git push origin main
```
## 我的`token`
```text
git remote set-url origin  https://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@github.com/StathamAB/website.git
git push origin main
```
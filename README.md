# AriaNg 网站

[AriaNg](https://github.com/mayswind/AriaNg/releases) 发布新版本后，可以使用 Github 的 Actions 自动更新 AriaNg 网站

## 为存储库创建配置变量

Settings -> Secrets and variables -> Actions -> Variables -> New repository variable

```
Name: CNAME
Value: 域名
```

```
Name: README
Value: README.md 内容
```

## 使用

Actions -> Publish -> Run workflow

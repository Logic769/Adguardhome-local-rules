# AdGuard Home 本地规则

## 项目说明

这是一个用于 AdGuard Home 的规则集合，包含黑名单和白名单规则。规则会通过 GitHub Actions 定时更新并发布到 releases，方便用户订阅。

## 规则内容

- **blacklist.txt** - 包含需要阻止的域名
- **whitelist.txt** - 包含需要允许的域名

## 订阅链接

### 黑名单订阅
```
https://github.com/用户名/Adguardhome-local-rules/releases/latest/download/blacklist.txt
```

### 白名单订阅
```
https://github.com/用户名/Adguardhome-local-rules/releases/latest/download/whitelist.txt
```

## 使用方法

1. 打开 AdGuard Home 管理界面
2. 进入 **过滤器** > **DNS 拦截列表**（黑名单）或 **DNS 允许列表**（白名单）
3. 点击 **添加阻止列表** 或 **添加允许列表**
4. 粘贴上面的订阅链接
5. 点击 **保存**

## 更新频率

规则会每天自动更新并发布到 releases。

## 贡献

欢迎提交 PR 来改进规则。

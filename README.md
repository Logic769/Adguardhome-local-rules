# AdGuard Home 本地规则

## 项目说明

这是一个用于 AdGuard Home 的规则集合。包含黑名单和白名单规则。规则会通过 GitHub Actions 定时更新并发布到 releases。

作为 `https://github.com/Logic769/AdguardHome-Rules` 的规则补充。

## 规则内容

- **blacklist.txt** - 包含需要阻止的域名
- **whitelist.txt** - 包含需要允许的域名

## 订阅链接

### 黑名单订阅
```
https://raw.githubusercontent.com/Logic769/Adguardhome-local-rules/main/blacklist.txt
```

### 白名单订阅
```
https://raw.githubusercontent.com/Logic769/Adguardhome-local-rules/main/whitelist.txt
```

> **注意**：以上链接直接指向仓库中的最新文件，确保订阅链接始终有效。

## 使用方法

1. 打开 AdGuard Home 管理界面
2. 进入 **过滤器** > **DNS 拦截列表**（黑名单）或 **DNS 允许列表**（白名单）
3. 点击 **添加阻止列表** 或 **添加允许列表**
4. 粘贴上面的订阅链接
5. 点击 **保存**

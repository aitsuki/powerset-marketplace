# Powerset Marketplace

## 安装插件

### Codex

添加市场并安装插件：

```sh
codex plugin marketplace add aitsuki/powerset-marketplace
codex plugin add powerset@powerset-marketplace
```

再次添加市场（codex插件市场的奇葩更新方式），更新：

```sh
codex plugin marketplace add aitsuki/powerset-marketplace
codex plugin remove powerset@powerset-marketplace
codex plugin add powerset@powerset-marketplace
```



### Claude Code

添加市场并安装插件：

```sh
claude plugin marketplace add aitsuki/powerset-marketplace
claude plugin install powerset@powerset-marketplace
```

更新:

```sh
claude plugin marketplace update
claude plugin update powerset@powerset-marketplace
```

# badge-lab

GitHub 成就徽章（Achievements）速查与打卡记录。这个小仓库的唯一用途是记录徽章的获取条件与解锁进度。

## 徽章速查

| 徽章 | 获取条件 | 门槛（默认 → 金） |
| --- | --- | --- |
| 🎯 Quickdraw | 创建 issue / PR 后 5 分钟内关闭 | 1 |
| 🎲 YOLO | 合并未经 review 的 PR | 1 |
| 🦈 Pull Shark | 公开仓库中被合并的 PR | 2 / 16 / 128 / 1024 |
| 🤝 Pair Extraordinaire | PR 内含 Co-authored-by 且被合并 | 1 / 10 / 24 / 48 |
| 🧠 Galaxy Brain | Discussions 回答被标为 accepted | 2 / 8 / 16 / 32 |
| ⭐ Starstruck | 单个公开仓库获得 star | 16 / 128 / 512 / 4096 |
| 💖 Public Sponsor | 通过 GitHub Sponsors 赞助他人 | 1 |

## 说明

- 私有仓库的 PR 不计入 Pull Shark。
- 徽章为异步计算，通常 24–48 小时后才在个人主页显示。
- `Heart On Your Sleeve`、`Open Sourcerer` 目前处于停用状态，无法获取。

## 进度

- 2026-10-21：建立仓库，开始记录。

## Co-authored-by 写法

在 commit message 末尾追加一行，邮箱需与该 GitHub 账号绑定：

```
Co-authored-by: 对方用户名 <对方邮箱>
```

PR 被合并后即计入 Pair Extraordinaire（默认档 1 次）。自己给自己署名不会计数。

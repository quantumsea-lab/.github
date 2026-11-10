# quantumsea-lab

量子海工作室。2026.11.09 – 2027.01.31，12 周一个周期，一次只扛一个主交付。

## 两个账号怎么分工

| 账号 | 身份 | 负责 |
| --- | --- | --- |
| [benrenafool](https://github.com/benrenafool) | 组织 Owner | 组织设置、仓库可见性、Secrets、打包与发版（tag + Release）、计费；对外发言 |
| [afoolquantum](https://github.com/afoolquantum) | 暂未加入组织，以 fork + PR 参与 | 只读、提意见、从零跑通验证（陌生人视角）；不接触 Secrets |

副号目前不是组织成员：组织套餐只有 1 个成员座位，现阶段不为第二个账号扩座，所以以 fork + PR 的方式参与公开仓库。等确实需要「第二 Owner 备份」时再处理成员身份。

## 协作规则

1. 密钥不进仓库：只放组织 Secrets，按仓库授权；提交前自查 `git diff` 里没有 token。
2. 发布只走 tag + Release，changelog 写在 Release 正文里。
3. 每个仓库的 README 回答三件事：**是什么 / 怎么跑 / 边界（不做什么）**。
4. 提交信息用「动词 + 对象」，例：`add: two-elements example`。
5. 大文件（帧包、录屏、素材）不进 Git。

## 仓库

| 仓库 | 用途 | 公开时间 |
| --- | --- | --- |
| [engine-5d](https://github.com/quantumsea-lab/engine-5d) | 五维引擎 | W2（11/20 起） |
| [site](https://github.com/quantumsea-lab/site) | 站点 + 取名落地页 | W4 |
| [anneal](https://github.com/quantumsea-lab/anneal) | 公开工具 | W11 |

## 节奏

周一至周四主攻 → 周五发布 + 周报 + 下周清单 → 周六学习 → 周日休息。

---

最后更新：2026-11-10

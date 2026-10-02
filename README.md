# 7gOS organization defaults

这个仓库给 `7gOS` 组织下**所有没有自己模板的仓库**提供默认值。它不是产品，是规范。

| 路径 | 作用 |
|---|---|
| `profile/README.md` | 组织首页展示的门面（本仓库必须 public 才会显示） |
| `ISSUE_TEMPLATE/` | 5 个启用的 Issue Form，与组织级 Issue Types 一一对应 |
| `ISSUE_TEMPLATE/_deferred/` | 3 个推迟的 form。GitHub 忽略子目录，所以既留存又不生效 |
| `PULL_REQUEST_TEMPLATE.md` | 组织内所有仓库的默认 PR 模板 |
| `SECURITY.md` | 全组织默认安全披露政策 |

## 认领关系

**认知类对象不开 Issue。** Note / Insight / Research / Decision 留在本地 vault ——
它们的价值在累积和被引用，没有终态，开成 Issue 只会得到一堆永不 done 的条目。

Issue 只装**有生命周期、需要推进与关闭**的东西：Idea / Initiative / Article / Task / Bug。

## 改名或新增模板前

先确认对应的 Issue Type 已存在。`_deferred/` 里那三个等研究搬上 GitHub 时再启用。

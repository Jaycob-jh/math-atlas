# Math Atlas｜已整合到脑科学知识库

数学教程与实验现已整合至 [brain-research-knowledge-base / 17_Mathematics](https://github.com/Jaycob-jh/brain-research-knowledge-base/tree/main/17_Mathematics)。后续内容更新在脑科学知识库维护；本仓库保留迁移前的文件与版本历史。

- [数学模块入口](https://github.com/Jaycob-jh/brain-research-knowledge-base/tree/main/17_Mathematics)
- [统一关键词、词条和章节检索工具](https://github.com/Jaycob-jh/brain-research-knowledge-base/tree/main/12_Tools/Knowledge_Search)
- [迁移来源与路径清单](https://github.com/Jaycob-jh/brain-research-knowledge-base/blob/main/17_Mathematics/References/migration.md)

迁移基准为 `math-changed-world` 分支的 `1a7b949d3f7da0d1966db43c926b76f0f7ade851`。目标仓库的访问权限沿用其原有设置。

---

以下为迁移前的使用说明，仅供历史查阅。

# 历史说明：Math Atlas｜数学知识与应用实验

这个仓库将数学概念、历史背景、核心推导与可复现应用实验放在同一条学习路径中。主要内容位于 [`mathematics-changed-the-world/`](mathematics-changed-the-world/)。

## 从哪里开始

| 目标 | 入口 |
|---|---|
| 按关键词找资料、教材与章节 | [关键词资料检索](mathematics-changed-the-world/docs/keyword-search.md) · [下载离线检索HTML](https://github.com/Jaycob-jh/math-atlas/blob/math-changed-world/mathematics-changed-the-world/docs/knowledge-search/index.html) |
| 按数学主题学习 | [知识库首页](mathematics-changed-the-world/docs/index.md) · [九个核心专题与数学主干](mathematics-changed-the-world/README.md) · [Fourier–Laplace–Z 专题桥梁](mathematics-changed-the-world/docs/bridges/01-transform-family.md) |
| 从最优化教材与课程进入 | [文再文最优化课程资源](mathematics-changed-the-world/docs/courses/optimization-pku-wenzw.md) · [学习路线](mathematics-changed-the-world/docs/courses/optimization-pku-wenzw-study-roadmap.md) |
| 运行应用实验 | [Python 实验目录](mathematics-changed-the-world/labs/README.md) |
| 核对资料使用程度 | [覆盖情况与证据边界](mathematics-changed-the-world/docs/coverage-matrix.md) · [逐项清单 TSV](mathematics-changed-the-world/docs/coverage-matrix.tsv) |

## 本地使用

```bash
cd mathematics-changed-the-world
python -m pip install -r requirements.txt -r requirements-labs.txt
python -m mkdocs serve
```

实验脚本位于 `labs/`；运行前先阅读对应页面的假设、输入和停止准则。网页构建成功或示例数值运行成功，不代表原始教材与讲义已全部审读，也不代表算法在其他数据上得到相同结果。

## 当前状态

知识库包含九个核心专题、二十条数学主干、一个 Fourier–Laplace–Z 专题桥梁，以及 24 个 Python 实验/教学脚本。最优化 Unit 07–10 已建立独立学习页；Unit 09 的三个合成数据项目已完成单一种子的基线和压力运行，并保留[来源页码与原始记录](mathematics-changed-the-world/labs/records/unit09/README.md)。Unit 07–08 新脚本仍未运行，Unit 10 没有已编译证明。资料索引中的“链接可读”“内容已审读”“代码已运行”分别记录，不互相替代。仓库历史上的 `readme.txt` 保留为早期 Git 练习记录。

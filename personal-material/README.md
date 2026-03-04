# 个人资料汇总

本文件夹汇总了个人主页项目中所有和个人相关的原始材料，作为重构个人主页的素材库。

注意，应用到个人主页网站展示内容，除了比如中文姓名等内容，须全部使用英文。

---

## 文件目录

### 文本文件

| 文件 | 内容描述 |
|------|---------|
| [basic-info.md](./basic-info.md) | 基本个人信息：姓名、邮箱、所在地、学校、所有对外链接（Google Scholar、GitHub、arXiv、ORCID等） |
| [bio.md](./bio.md) | 个人简介正文，即主页首页展示的自我介绍段落 |
| [cv.md](./cv.md) | 完整简历：教育背景、研究/工作经历、技能清单 |
| [publications.md](./publications.md) | 发表论文列表：每篇论文的完整元数据、摘要、作者、引用格式及 BibTeX |

### 图片文件（images/ 子文件夹）

| 文件 | 内容描述 |
|------|---------|
| [images/AUTHOR_KaiwenXiong.png](./images/AUTHOR_KaiwenXiong.png) | 个人头像（侧边栏展示用） |
| [images/Agent0-vl.png](./images/Agent0-vl.png) | 论文 Agent0-VL 的 teaser 图 |
| [images/RASWE_graphical_abstract.png](./images/RASWE_graphical_abstract.png) | 论文 Adaptive Sliding Window Estimator 的 teaser 图 |
| [images/ATP.png](./images/ATP.png) | 论文 Alignment Tipping Process 的 teaser 图 |

---

## 原始文件对应关系

| 本文件夹 | 原始文件位置 |
|---------|------------|
| basic-info.md | `_config.yml` → `author:` 字段 |
| bio.md | `_pages/about.md` |
| cv.md | `_pages/cv.md` |
| publications.md | `_publications/2025-11-25-Agent0-VL.md`、`_publications/2025-07-04-Adaptive-Sliding-Window-Estimator.md`、`_publications/2026-02-11-Alignment-Tipping-Process.md`、`files/*.bib` |
| images/AUTHOR_KaiwenXiong.png | `images/AUTHOR_KaiwenXiong.png` |
| images/Agent0-vl.png | `images/publication/Agent0-vl.png` |
| images/RASWE_graphical_abstract.png | `images/publication/RASWE_graphical_abstract.png` |

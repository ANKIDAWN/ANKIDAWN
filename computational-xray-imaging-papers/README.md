# Computational X-ray Imaging Paper Repository

这是一个长期追踪“计算 X 射线成像 / coherent X-ray imaging”方向新论文的仓库。PSI CXI group 的 publications 页面是初始种子源之一，但追踪范围不限于该小组。

GitHub 入口目标：`ANKIDAWN/ANKIDAWN` 下的 `computational-xray-imaging-papers/` 文件夹。

## 追踪范围

收录目标包括但不限于：

- coherent X-ray imaging
- computational X-ray imaging
- ptychography / ptychographic tomography / ptycho-laminography
- phase retrieval
- X-ray holography
- X-ray computed tomography / nanotomography
- SAXS imaging / small-angle X-ray scattering tensor tomography
- vector tomography / tensor tomography / dichroic tomography
- sparse, dynamic, 4D, operando or time-resolved X-ray imaging
- synchrotron / XFEL computational imaging methods
- 与上述方法强相关的材料、能源器件、催化、电池、磁性、生物组织、微电子和纳米结构应用论文

PSI CXI、Swiss Light Source/SLS、DORA PSI、相关 beamline 和成员论文会被优先追踪；其他机构的新论文只要明显推进上述方向，也应纳入。

## 当前状态

- 初始来源：https://www.psi.ch/en/cxi/publications
- 初始化收录：157 篇
- 年份范围：2010-2026
- 当前任务：每周自动检查新增论文，并为每篇新增论文生成中文讲解

## 仓库结构

- `config/scope.json`: 方向范围、关键词、种子网址、纳入/排除规则。
- `data/papers.json`: 已收录论文的结构化索引。
- `papers/index.md`: 157 篇论文的标题索引和 DOI 链接。
- `papers/by-year/`: GitHub 浏览友好的按年份聚合讲解。
- `scripts/update_papers.py`: 增量抓取种子源并更新索引。
- `logs/`: 每次更新记录。

## 自动更新

已创建 Codex 每周自动任务：`Computational X-ray Imaging 论文仓库每周更新`。

每周任务会搜索整个 computational/coherent X-ray imaging 方向，不限于 PSI CXI，并更新新增论文讲解。
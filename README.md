# quanttide-execute
量潮执行管理

## 概述

量潮执行管理（quanttide-execute）是量潮知识管理体系中的**执行管理**领域，涵盖任务执行、流程编排、工作流管理与自动化调度等核心能力。

## 领域边界

- **任务执行**：任务定义、调度策略、执行引擎
- **流程编排**：流程建模、规则引擎、状态管理
- **工作流管理**：工作流设计、审批流转、版本管理
- **自动化调度**：定时任务、事件触发、重试机制

## 子模块

| 路径 | 说明 |
|------|------|
| `apps/qtadmin` | 量潮管理后台——执行管理前台 (git submodule → qtadmin) |
| `apps/qtcloud-execute` | 执行云服务 (git submodule → qtcloud-execute) |
| `packages/quanttide-execute-toolkit` | 执行管理工具箱 (git submodule → quanttide-execute-toolkit) |
| `examples/default` | 执行管理实验室 (git submodule → quanttide-laboratory-of-execution-management) |
| `data/context` | 执行管理语境 (git submodule → quanttide-context-of-execution-management) |
| `data/journal` | 执行管理工作日志 (git submodule → quanttide-journal-of-execution-management) |
| `data/profile` | 执行管理工作档案 (git submodule → quanttide-profile-of-execution-management) |
| `data/intention` | 执行管理意图 (git submodule → quanttide-intention-of-execution-management) |
| `data/roadmap` | 执行管理路线图 (git submodule → quanttide-roadmap-of-execution-management) |
| `data/insight` | 执行管理洞察 (git submodule → quanttide-insight-of-execution-management) |
| `data/brochure` | 执行管理宣传册 (git submodule → quanttide-brochure-of-execution-management) |
| `data/report` | 执行管理报告 (git submodule → quanttide-report-of-execution-management) |
| `data/library` | 执行管理参考 (git submodule → quanttide-library-of-execution-management) |
| `data/history` | 执行管理历史 (git submodule → quanttide-history-of-execution-management) |
| `data/archive` | 执行管理归档 (git submodule → quanttide-archive-of-execution-management) |
| `docs/bylaw` | 执行管理章程 (git submodule → quanttide-bylaw-of-execution-management) |
| `docs/handbook` | 执行管理工作手册 (git submodule → quanttide-handbook-of-execution-management) |
| `docs/specification` | 执行管理标准 (git submodule → quanttide-specification-of-execution-management) |
| `docs/tutorial` | 执行管理教程 (git submodule → quanttide-tutorial-of-execution-management) |
| `docs/essay` | 执行管理札记 (git submodule → quanttide-essay-of-execution-management) |
| `docs/gallery` | 执行管理案例集 (git submodule → quanttide-gallery-of-execution-management) |

子模块操作：`git submodule update --init --recursive`；子模块内部改动须先在子模块仓库内提交，再回主仓库更新指针。

## 许可

[CC BY 4.0](LICENSE)

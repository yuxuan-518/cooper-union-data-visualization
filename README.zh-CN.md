# 数据可视化与叙事

[English](README.md) | **简体中文**

这个仓库整理了我在 **2024 年 Cooper Union STEM Saturdays 项目 Inventor’s Lab: Data Visualization** 中完成的数据可视化材料，包括一个美国就业数据期末项目，以及四个课堂练习。

## PDF 阅读版

[项目讲解与学习收获 — 中文 PDF](docs/Project_and_Learning_Chinese.pdf) · [English PDF](docs/Project_and_Learning_English.pdf)

[期末演示文稿 — PDF 阅读版](final-project/employment-analysis/final-presentation.pdf) · [原始 PowerPoint](final-project/employment-analysis/final-presentation.pptx)

演示 PDF 保留原文和页序，重新排版文字并配合部分图表总览；原 PPT 保留原始布局和动画构件。

## 期末项目：美国就业数据中的群体差异

这个项目把标注为 **1979—2022 年的 44 行年度就业数据**整理成一组可比较的图表，让听众看到不同年龄、教育背景和性别的就业情况如何随时间变化。最终成果是包含 **7 个工作表的 Excel 文件、22 页演示文稿和中英双语讲稿**。听众可以先看总体趋势，再通过局部放大和差值图理解群体差距，不必逐行阅读原始表格。

年龄部分比较四个年龄段；学历部分比较五类教育背景，并计算高级学位与学士学位的差值；性别部分比较男女数据，也进一步查看不同年龄群体中的差距。折线图呈现时间变化，柱形图用于群体比较，差值图则把两组数据之间的距离单独展示出来。

原演示文稿署名为 **Shaoxuan Xiong（制作）** 和 **Richard Feng（编辑）**。讲稿保留了两位讲者的分工标记、排练提示和词汇注释。

[查看期末项目](final-project/employment-analysis) · [下载演示文稿](final-project/employment-analysis/final-presentation.pptx) · [查看 Excel 工作簿](final-project/employment-analysis/employment-analysis.xlsx) · [直接阅读双语讲稿](final-project/employment-analysis/speaker-notes.md)

![原期末演示文稿第 12 页中的不同教育背景就业比例比较](assets/employment-preview.png)

*这张图来自原演示文稿。不同曲线代表不同教育类别，保留了原图中的年份标注和数值。*

例如，原学历表中高级学位组与学士学位组在 **1979 年相差 7.8 个百分点，2015 年相差 0.3 个百分点**。把每年的差值画成另一张图，听众就能更直接地看到两组之间的距离。这是对表中变化的描述；年份对应关系和历史解释仍需进一步复核，具体记录在[数据说明](docs/DATA_NOTES.md)中。

[阅读完整项目讲解](final-project/employment-analysis/PROJECT_EXPLAINED.zh-CN.md)。

## 我在这门课中练习了什么

我练习了整理数值和分类字段，使用 Excel 计算计数、平均数、标准差和频数，并根据问题选择图表。Titanic 和硬币质量练习从单个记录、测量值入手，期末项目再把这些方法用于不同群体的年度数据比较。

我也练习了从直接比较数值，进一步转向差值和比例，并明确计算所用的分母。例如，“幸存者中一等舱乘客的占比”和“一等舱乘客的生还率”是两个不同的问题。理赔用时练习则让我比较，同一份数据使用不同图表时，读者更容易看清总量还是各部分之间的大小。

期末项目把表格处理、图表比较和口头表达连接起来。双语讲稿和合作演示让我练习分配讲述内容、衔接各部分，并用英语说明图表里的群体、时间范围和变化。[阅读完整学习收获](docs/LEARNING.zh-CN.md)。

## 课堂练习

| 练习 | 主要内容 | 查看材料 |
|---|---|---|
| Titanic 数据分析 | 乘客概况、年龄和票价分布、性别计数，以及幸存者的舱位构成。 | [工作簿与数据](exercises/titanic) |
| 硬币质量分析 | 硬币测量数据、描述统计、频数统计和正态分布密度计算。 | [工作簿与数据](exercises/penny-mass) |
| 图表比较 | 用两种图表展示理赔总用时及各阶段用时，包含练习提供的预测行。 | [工作簿与数据](exercises/chart-comparison) |
| 节目选择建议 | 用 5 页演示文稿比较节目受欢迎程度、观众群体和制作成本。 | [演示文稿](exercises/program-selection) |

## 文件使用

仓库保留了 **7 份未改动的原始作业文件**，只调整了文件名和存放位置。另提供 CSV 数据和讲稿文字版，方便直接在 GitHub 阅读；Excel 原件中的公式、图表和排版仍然保留。

- [文件索引与原始文件名](docs/FILE_INDEX.md)
- [数据来源与署名](docs/SOURCES.md)
- [数据定义与解读说明](docs/DATA_NOTES.md)


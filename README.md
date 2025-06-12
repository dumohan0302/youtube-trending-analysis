

\## 项目简介

本项目使用 Kaggle 提供的 YouTube Trending Video 数据集，探索影响视频热度的关键因素，包括播放量、点赞数、标题长度、标签数量和发布时间等。
https://www.kaggle.com/datasets/datasnaek/youtube-new


##原始数据 

540MB



\## 使用工具

\- Python

\- Pandas

\- Matplotlib / Seaborn

\- Jupyter Notebook



\## 分析目标

\- 数据清洗与预处理

\- 描述性统计与可视化

\- 内容特征对播放量/热度的影响分析

\- 输出结论与优化建议



\## 项目结构

notebooks/01_eda_trending_analysis.ipynb

youtube-trending-analysis/
├── data/archive/         # 放置 CSV 数据
├── notebooks/            # Jupyter Notebook 分析脚本
├── src/
│   └── data_utils.py     # 数据加载与预处理函数
├── output/
│   ├── figures/          # 图表输出
│   └── tables/           # 表格输出
├── docs/                 # 报告与演示材料
├── run_analysis.py       # 脚本入口：批量读取并检查数据
├── requirements.txt      # Python 依赖（pandas, numpy, seaborn…）
├── environment.yml       # Conda 环境配置
├── .gitignore            # 忽略虚拟环境、缓存、输出文件等
└── README.md             # 完整安装、运行说明 & 目录结构 & 数据来源


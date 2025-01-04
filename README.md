# 项目简介
本项目旨在分析影响在线音乐歌单播放量的各种因素，以网易云音乐为例进行研究。通过对歌单的歌单作者名、歌单收藏量、歌单分享数、歌单评论数、歌单创建时间、歌单歌曲数、作者粉丝数、歌单话题、歌单高频词、歌单名称和歌单简介等特征进行数据处理和分析，从而试图找出哪些因素对歌单的播放量有显著影响，并从 $R^2$ 和MAE两个指标来评价多元线性回归和随机森林模型再回归拟合方面的优劣。项目使用了 Python 语言进行数据清洗、特征工程和可视化，并利用统计模型和机器学习方法进行分析。

# 复现说明
## 运行环境
操作系统: 适用于 Windows、Linux 或 macOS

Python 版本: Python 3.8 或更高版本

以下是项目中使用的主要 Python 包及其版本：
- `numpy`: 1.26.4
- `pandas`: 2.2.2
- `matplotlib`: 3.8.4
- `seaborn`: 0.12.2
- `plotnine`: 0.13.6
- `sklearn`: 1.5.1
- `statsmodels`: 0.14.2
## 复现步骤
## 1. 安装 Python 和相关包
   - 确保已安装 Python 3.8 或更高版本。
   - 使用 pip 安装所需的包：
## 2. 获取数据
项目中使用的数据文件 `music.csv` 需要从指定的数据源获取（链接:https://pan.baidu.com/s/1SUn-UgV8Yk7R-gtmXzTUTQ 提取码: pyyj）。
## 3. 运行代码
打开项目中的 Jupyter Notebook 文件（在线音乐歌单播放量影响因素分析 ——以网易云为例.ipynb）。
依次运行 Notebook 中的各个单元格，进行数据处理、特征工程、可视化和分析。
## 4. 查看结果
在 Notebook 中查看生成的图表和分析结果，理解不同因素对歌单播放量的影响。
# 注意事项
在运行代码前，确保数据文件路径正确，或根据实际情况修改代码中的文件路径。如果在运行过程中遇到任何问题，可以查看项目中的文档或联系项目作者寻求帮助。
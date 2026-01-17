# HNU_SYS_2023 数据集 / Dataset

湖南大学信号与系统课程习题数据集，包含2023年课程习题和知识点关联信息。

Hunan University Signals and Systems course exercise dataset, containing 2023 course exercises and knowledge-point associations.

## 文件 / Files

- **HNU_SYS_2023.txt**: 课程习题和知识点数据 / Course exercises and knowledge point data
- **question2skill.csv**: 习题与技能点关联矩阵 / Exercise-skill association matrix
- **process_hnu_sys2023.py**: 数据预处理脚本 / Data preprocessing script

## 应用 / Applications

教育数据分析、知识点关联研究、推荐系统开发

Educational data analysis, knowledge-point association research, recommendation system development

## 数据预处理脚本 / Data Preprocessing Script

[process_hnu_sys2023.py](process_hnu_sys2023.py) 脚本用于将原始数据转换为统一格式：

- 输入：学生答题记录 (HNU_SYS_2023.txt) 和题目-知识点映射 (question2skill.csv)
- 输出：标准化的学生答题序列文件和映射表
- 功能：重新编号、格式转换、统计信息生成

The [process_hnu_sys2023.py](process_hnu_sys2023.py) script converts raw data to a unified format:

- Input: Student response records (HNU_SYS_2023.txt) and question-skill mappings (question2skill.csv)
- Output: Standardized student response sequence files and mapping tables
- Features: Re-numbering, format conversion, statistics generation

## 许可证 / License

CC BY-SA 4.0

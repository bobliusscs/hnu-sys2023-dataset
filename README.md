<div align="center">

# HNU_SYS_2023 数据集 / Dataset

<p>
  <a href="README.md">简体中文</a> | <a href="README_EN.md">English</a>
</p>

</div>

---

## 简介

湖南大学信号与系统课程习题数据集，包含2023年课程习题和知识点关联信息。

## 文件

- **HNU_SYS_2023.txt**: 课程习题和知识点数据
- **question2skill.csv**: 习题与技能点关联矩阵
- **process_hnu_sys2023.py**: 数据预处理脚本

## 应用

教育数据分析、知识点关联研究、推荐系统开发

## 数据预处理脚本

[process_hnu_sys2023.py](process_hnu_sys2023.py) 脚本用于将原始数据转换为统一格式：

- 输入：学生答题记录 (HNU_SYS_2023.txt) 和题目-知识点映射 (question2skill.csv)
- 输出：标准化的学生答题序列文件和映射表
- 功能：重新编号、格式转换、统计信息生成

## 许可证

CC BY-SA 4.0
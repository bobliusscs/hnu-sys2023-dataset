<div align="center">

# HNU_SYS_2023 Dataset

<p>
  <a href="README_EN.md">English</a> | <a href="README.md">简体中文</a>
</p>

</div>

---

## Files

- **HNU_SYS_2023.txt**: Course exercises and knowledge point data
- **question2skill.csv**: Exercise-skill association matrix
- **process_hnu_sys2023.py**: Data preprocessing script

## Applications

Educational data analysis, knowledge-point association research, recommendation system development

## Data Preprocessing Script

The [process_hnu_sys2023.py](process_hnu_sys2023.py) script converts raw data to a unified format:

- Input: Student response records (HNU_SYS_2023.txt) and question-skill mappings (question2skill.csv)
- Output: Standardized student response sequence files and mapping tables
- Features: Re-numbering, format conversion, statistics generation

## License

CC BY-SA 4.0
# The Teyvat Dataset
### Genshin Impact Character Data Analysis

An exploratory data analysis project using Python and pandas to investigate character data from Genshin Impact.

This project started as a hands-on exercise to practice Python libraries and has evolved into an opportunity to explore data cleaning, transformation, aggregation, and visualization.

## Project Overview

The goal is to explore the structure of the character dataset, identify patterns in character attributes, and communicate findings through clear visualizations.

### Research Questions

- How are characters distributed across elemental Visions?
- Which weapon types are most common?
- How does character rarity vary across the dataset?
- How are characters distributed across regions?
- How has the character roster evolved over release dates?

These questions will be investigated using the available data. Findings will be documented after the analysis is validated.

## Tools and Technologies

- **Python** — data analysis
- **Pandas** — data manipulation and cleaning
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical charts
- **Jupyter Notebook / Google Colab** — interactive analysis

## Repository Structure

```text
genshin_char_da/
├── README.md
├── genshin_characters_v1.csv
└── genshin_data_analysis.ipynb
```

## Dataset

The project uses a CSV dataset containing character attributes, including:

- Character name and rarity
- Elemental Vision and weapon type
- Region and release date
- Character model and other descriptive attributes
- Character statistics at different ascension levels

The original dataset contains 94 records and 89 columns. The notebook will validate its structure and data quality before conducting further analysis.

**Source:** [Genshin Impact Characters Dataset on Kaggle](https://www.kaggle.com/datasets/ngtengsuan/genshin-impact-characters-dataset)

## Project Workflow

1. Load and inspect the dataset.
2. Evaluate missing values and duplicate records.
3. Validate data types and prepare relevant columns.
4. Explore categorical variables and numerical attributes.
5. Create visualizations to answer the research questions.
6. Summarize findings and limitations.

## How to Run

1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open `genshin_data_analysis.ipynb` in Jupyter Notebook or upload it to Google Colab.
4. Run the notebook cells in order.

## Project Status

**In progress.** Data validation, exploratory analysis, visualizations, and documented findings are being developed incrementally.

## Disclaimer

Genshin Impact is a game developed by HoYoverse. This is an independent, educational data analysis project and is not affiliated with or endorsed by HoYoverse.

## Author

Created by [kekozeus](https://github.com/kekozeus) as part of a learning journey in Python and data analysis.

[View the repository](https://github.com/kekozeus/genshin_char_da)

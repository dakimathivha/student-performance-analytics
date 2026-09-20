# Student Performance Analytics

An exploratory data analysis (EDA) project examining student performance, engagement, and teaching-related variables using Python.

## Project Questions

- How are students distributed across performance categories?
- Is final grade associated with attendance, weekly study hours, assignments completed, or midterm grade?

## Tools

Python, pandas, Matplotlib, and Jupyter Notebook in Visual Studio Code.

## Dataset

Source: [Student Performance & Teaching Dataset on Kaggle](https://www.kaggle.com/datasets/zara2099/student-performance-and-teaching-dataset/data)

The dataset contains 1,000 records and 15 columns. Whether the records are real or synthetic has not been confirmed.

## Key Findings

- **Good** was the most common student performance category (41.3%); **Poor** was the least common (9.3%).
- Pearson correlations with final grade were close to zero for attendance (0.012), weekly study hours (-0.039), assignments completed (-0.002), and midterm grade (-0.012).
- These results indicate little to no **linear association** in this dataset. They do not establish cause and effect.

## Explore the Analysis

Open [`notebooks/student_performance_analysis.ipynb`](notebooks/student_performance_analysis.ipynb) to view the data checks, visualisations, calculations, and interpretations.

The notebook reads the CSV from `data/student_performance.csv`. To run it, open the notebook in VS Code with a Python environment containing pandas and Matplotlib, then run the cells from top to bottom.

## Limitations

The dataset's real-world provenance has not been confirmed, so the findings should not be generalised to real student populations. Pearson correlation measures linear association and does not capture every possible relationship.

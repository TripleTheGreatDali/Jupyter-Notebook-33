readme_content = """
# Data for Data Visualization

This repository contains datasets sourced from [Alexis Cook’s Data for Data Visualization](https://www.kaggle.com/datasets/alexisbcook/data-for-datavis) on Kaggle. These datasets are ideal for practicing data visualization and analysis techniques.

## Datasets Overview

The collection includes the following CSV files:

- **cancer.csv**: General cancer-related data for analysis.
- **cancer_b.csv**: A variant of cancer dataset (type B).
- **cancer_m.csv**: A variant of cancer dataset (type M).
- **candy.csv**: Candy preferences and survey data.
- **fifa.csv**: FIFA player statistics and attributes.
- **flight_delays.csv**: Flight delay information for airline analysis.
- **ign_scores.csv**: Video game scores and ratings from IGN.
- **insurance.csv**: Health insurance data with demographic details.
- **iris.csv**: Classic iris dataset for species classification.
- **iris_setosa.csv**: Iris Setosa species subset.
- **iris_versicolor.csv**: Iris Versicolor species subset.
- **iris_virginica.csv**: Iris Virginica species subset.
- **museum_visitors.csv**: Museum visitor statistics.
- **spotify.csv**: Spotify song metadata and statistics.

Each dataset allows you to explore different types of data structures, relationships, and visualization techniques.

## Dataset Source

All datasets are publicly available on Kaggle:

[https://www.kaggle.com/datasets/alexisbcook/data-for-datavis](https://www.kaggle.com/datasets/alexisbcook/data-for-datavis)

## License

The datasets are provided under the [Kaggle Terms of Service](https://www.kaggle.com/terms).
"""

# Write README.md to the current folder
with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)

print("README.md has been created with dataset list.")

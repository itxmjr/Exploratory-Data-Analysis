# 📊 Exploratory Data Analysis - Iris Dataset

![Python](https://img.shields.io/badge/Python-3.13+-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

A focused **Exploratory Data Analysis (EDA)** of the famous Iris flower dataset, demonstrating statistical analysis, data visualization, and insights discovery using Python's powerful data science libraries.

## ✨ Features

* **Basic Data Inspection**: Shape, columns, data types, and missing value checks.
* **Statistical Analysis**: Descriptive statistics for all numerical features.
* **Clear Visualizations**: Scatter plots, pair plots, and box plots for understanding feature relationships.
* **Species Comparison**: Visual comparison of Setosa, Versicolor, and Virginica.
* **Beginner-Friendly Notebook**: Simple, readable, and well-commented EDA workflow.

## 🚀 Demo

The notebook includes visual analysis of:

* Sepal length vs sepal width
* Petal length vs petal width
* Pair plots showing relationships across all features
* Species-wise box plots

## 📸 Screenshots

<div align="center">
<table>
<tr>
<td align="center"><b>Sepal Length vs Sepal Width</b><br><img src="assets/Sepal Length vs Sepal Width.png" alt="Sepal Length vs Sepal Width" width="380"/></td>
<td align="center"><b>Petal Length vs Petal Width</b><br><img src="assets/Petal Length vs Petal Width.png" alt="Petal Length vs Petal Width" width="380"/></td>
</tr>
<tr>
<td align="center" colspan="2"><b>Pairwise Relationships</b><br><img src="assets/Pairwise Relationships.png" alt="Pairwise Relationships" width="550"/></td>
</tr>
<tr>
<td align="center" colspan="2"><b>Feature Comparison by Species</b><br><img src="assets/Feature Comparison by Species.png" alt="Feature Comparison by Species" width="550"/></td>
</tr>
</table>
</div>

## 🛠️ Tech Stack

* **[Python](https://www.python.org/)**: Core programming language (3.13+).
* **[Jupyter Notebook](https://jupyter.org/)**: Interactive analysis environment.
* **[Pandas](https://pandas.pydata.org/)**: Data manipulation and analysis.
* **[Matplotlib](https://matplotlib.org/)**: Data visualization.
* **[Seaborn](https://seaborn.pydata.org/)**: Statistical visualizations.

## 📦 Installation

Ensure you have Python 3.13 or higher installed.

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/itxmjr/Exploratory-Data-Analysis.git
    cd Exploratory-Data-Analysis
    ```

2.  **Install Dependencies**
    It is recommended to use a virtual environment.

    Using `pip`:
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

    Using `uv`:
    ```bash
    uv sync
    ```

## 🎮 Usage

1.  **Launch Jupyter Notebook**
    Execute the following command in your terminal:
    ```bash
    jupyter notebook notebooks/iris_eda.ipynb
    ```

2.  **Explore the Analysis**
    - Load and inspect the dataset
    - Review statistical summaries
    - Analyze visual patterns across species

3.  **Customize**
    - Modify visualizations to explore different feature combinations
    - Add your own analysis cells
    - Experiment with different chart types

## 📂 Project Structure

```
Exploratory-Data-Analysis/
├── assets/                 # Visualization screenshots
│   ├── Feature Comparison by Species.png
│   ├── Pairwise Relationships.png
│   ├── Petal Length vs Petal Width.png
│   └── Sepal Length vs Sepal Width.png
├── notebooks/
│   └── iris_eda.ipynb      # Main analysis notebook
├── .gitignore              # Python gitignore configuration
├── LICENSE                 # MIT License
├── pyproject.toml          # Project configuration and dependencies
├── uv.lock                 # Dependency lock file
└── README.md               # Project documentation
```

## 📊 Dataset

This analysis uses the **Iris Dataset**, one of the most famous datasets in machine learning and statistics:

- **Source**: Built-in dataset from Seaborn library
- **Size**: 150 samples
- **Features**: 4 numerical features (sepal length, sepal width, petal length, petal width)
- **Target**: 3 species classes (Setosa, Versicolor, Virginica)
- **Use Case**: Classification, clustering, and statistical analysis

## 🔍 Key Findings

- Petal features provide clear separation between species
- Setosa is easily distinguishable from the other two species
- Strong positive correlation between petal length and petal width

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or additional analyses, feel free to open an issue or submit a pull request.

1.  Fork the repository.
2.  Create your feature branch (`git checkout -b feature/NewAnalysis`).
3.  Commit your changes (`git commit -m 'Add new analysis'`).
4.  Push to the branch (`git push origin feature/NewAnalysis`).
5.  Open a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <sub>Built with ❤️ by M Jawad ur Rehman using Python and Jupyter Notebook.</sub>
</div>

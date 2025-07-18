# Data Science Fundamentals Notebooks

This repository contains a collection of Jupyter notebooks covering essential data science concepts and tools. These notebooks are designed to provide hands-on learning experiences with Python's most important data science libraries.

## 📁 Notebook Contents

### 1. **Numpy_Basics.ipynb**
**Foundation of Numerical Computing**
- Introduction to NumPy arrays and data types
- Array creation, indexing, and slicing
- Mathematical operations and broadcasting
- Linear algebra operations
- Array manipulation and reshaping
- Statistical functions and random number generation

**Prerequisites:** Basic Python knowledge  
**Key Libraries:** `numpy`

### 2. **Pandas Basics.ipynb**
**Data Manipulation and Analysis**
- DataFrame and Series creation and manipulation
- Data loading from various file formats (CSV, Excel, JSON)
- Data selection, filtering, and indexing
- Handling missing data and duplicates
- Data aggregation and grouping operations
- Merging and joining datasets
- Data transformation and cleaning techniques

**Prerequisites:** Numpy_Basics.ipynb  
**Key Libraries:** `pandas`, `numpy`

### 3. **Data Preprocessing.ipynb**
**Preparing Data for Analysis**
- Data quality assessment and profiling
- Handling missing values (imputation strategies)
- Outlier detection and treatment
- Feature engineering and selection
- Categorical variable encoding
- Text data preprocessing
- Data validation and consistency checks

**Prerequisites:** Pandas Basics.ipynb  
**Key Libraries:** `pandas`, `numpy`, `scikit-learn`

### 4. **Data Standardization.ipynb**
**Feature Scaling and Normalization**
- Understanding the importance of data standardization
- Min-Max scaling (normalization)
- Z-score standardization
- Robust scaling for outlier-resistant preprocessing
- Unit vector scaling
- Comparing different scaling methods
- When to apply each scaling technique

**Prerequisites:** Data Preprocessing.ipynb  
**Key Libraries:** `pandas`, `numpy`, `scikit-learn`

### 5. **Matplotlib_Basics.ipynb**
**Data Visualization Fundamentals**
- Creating basic plots (line, scatter, bar, histogram)
- Customizing plot appearance (colors, labels, titles)
- Working with subplots and multiple figures
- Saving and exporting plots
- Plot formatting and styling
- Creating publication-ready visualizations

**Prerequisites:** Pandas Basics.ipynb  
**Key Libraries:** `matplotlib`, `numpy`, `pandas`

### 6. **Seaborn Basics.ipynb**
**Statistical Data Visualization**
- Statistical plotting with Seaborn
- Distribution plots (histograms, KDE, box plots)
- Relationship plots (scatter plots, regression plots)
- Categorical data visualization
- Heatmaps and correlation matrices
- Styling and theming plots
- Integration with Pandas DataFrames

**Prerequisites:** Matplotlib_Basics.ipynb  
**Key Libraries:** `seaborn`, `matplotlib`, `pandas`, `numpy`

## 🚀 Getting Started

### Installation Requirements

Create a virtual environment and install the required packages:

```bash
# Create virtual environment
python -m venv data_science_env

# Activate virtual environment
# On Windows:
data_science_env\Scripts\activate
# On macOS/Linux:
source data_science_env/bin/activate

# Install required packages
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Alternative Installation with Conda

```bash
# Create conda environment
conda create -n data_science python=3.9

# Activate environment
conda activate data_science

# Install packages
conda install numpy pandas matplotlib seaborn scikit-learn jupyter-notebook
```

### Running the Notebooks

1. Navigate to the project directory
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the notebooks in the recommended order (see Learning Path below)

## 📚 Recommended Learning Path

For beginners, follow this sequence:

1. **Numpy_Basics.ipynb** - Build your foundation
2. **Pandas Basics.ipynb** - Learn data manipulation
3. **Data Preprocessing.ipynb** - Master data cleaning
4. **Data Standardization.ipynb** - Understand feature scaling
5. **Matplotlib_Basics.ipynb** - Create basic visualizations
6. **Seaborn Basics.ipynb** - Advanced statistical plots

## 🎯 Learning Objectives

By completing these notebooks, you will:

- Understand the fundamentals of numerical computing with NumPy
- Master data manipulation and analysis with Pandas
- Learn essential data preprocessing techniques
- Understand when and how to standardize data
- Create effective data visualizations
- Build a solid foundation for advanced data science topics

## 📊 Sample Datasets

These notebooks use various sample datasets including:
- Built-in datasets from libraries (iris, tips, titanic)
- Generated synthetic data for demonstration
- Real-world datasets for practical examples

## 🔧 Troubleshooting

**Common Issues:**
- **Import errors:** Ensure all required packages are installed
- **Kernel issues:** Restart the Jupyter kernel if notebooks become unresponsive
- **Memory errors:** Close unused notebooks and clear output cells

## 📖 Additional Resources

- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

## 🤝 Contributing

Feel free to contribute by:
- Adding new examples or exercises
- Improving existing code and explanations
- Fixing bugs or typos
- Suggesting new topics or datasets

## 📝 License

This project is open source and available under the MIT License.

---

**Happy Learning!** 🎉

These notebooks provide a comprehensive introduction to the essential tools and techniques in data science. Work through them at your own pace and don't hesitate to experiment with the code examples.

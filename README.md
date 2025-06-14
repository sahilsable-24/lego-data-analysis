# LEGO Data Analysis

This project provides an exploratory data analysis (EDA) of LEGO sets, themes, and colors using a collection of CSV files and a Jupyter Notebook. The goal is to derive insights into the history, evolution, and diversity of LEGO products over the years.

## 📁 Project Structure

```
.
├── Lego_Analysis.ipynb     # Jupyter Notebook with the analysis
├── colors.csv              # Dataset with information about LEGO colors
├── sets.csv                # Dataset containing details of LEGO sets
├── themes.csv              # Dataset with LEGO themes and sub-themes
```

## 📊 Dataset Descriptions

- **colors.csv**: Contains information on LEGO colors, including name, RGB value, and transparency.
- **sets.csv**: Includes data on LEGO sets from different years, such as set number, name, year, theme ID, and number of parts.
- **themes.csv**: Lists various LEGO themes and associated theme IDs, along with hierarchical relationships.

## 📒 Notebook Overview

The `Lego_Analysis.ipynb` notebook covers:

- Loading and cleaning data
- Exploratory data analysis using `pandas` and `matplotlib`
- Visualizations such as:
  - Number of sets released per year
  - Growth of LEGO parts over time
  - Distribution of transparent vs. non-transparent colors
  - Top themes by number of sets

## 🛠️ Requirements

To run the notebook locally, make sure you have the following Python libraries installed:

```bash
pip install pandas matplotlib jupyter
```

Or open the notebook in [Google Colab](https://colab.research.google.com/) for easy online execution.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sahilsable-24/lego-data-analysis.git
   cd lego-data-analysis
   ```

2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Lego_Analysis.ipynb
   ```

## 📌 License

This project is open-source and available under the MIT License.

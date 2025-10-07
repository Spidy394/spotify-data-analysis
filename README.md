# 🎵 Spotify Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-Educational-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)](https://github.com/Spidy394/spotify-data-analysis)

A comprehensive exploratory data analysis (EDA) of Spotify tracks dataset to uncover patterns, trends, and insights in music characteristics and popularity. This project provides data-driven insights for music streaming platforms, artists, and industry stakeholders through advanced statistical analysis and visualization techniques.

## 📊 Dataset Overview

The analysis utilizes a comprehensive Spotify tracks dataset (`spotify_dataset.zip`) containing:

- **Track Metadata**: ID, name, artist, album, release year
- **Audio Features**: Danceability, energy, valence, acousticness, loudness, tempo, speechiness, instrumentalness, liveness
- **Popularity Metrics**: Track popularity scores (0-100 scale)
- **Musical Properties**: Key, time signature, duration, and mode
- **Temporal Information**: Multi-decade span for music evolution analysis

### Dataset Preparation

The dataset comes compressed in `spotify_dataset.zip`. Extract it before running the analysis:

```bash
# Extract the dataset
unzip spotify_dataset.zip
```

## 🔍 Complete Analysis Structure

### ✅ **Completed Analysis Sections:**

1. **Data Loading & Initial Exploration** - Dataset import and initial assessment
2. **Data Cleaning & Preprocessing** - Missing value handling, outlier detection, quality improvements
3. **Univariate Analysis** - Individual variable distributions and descriptive statistics
4. **Categorical Variables Analysis** - Artist, key, and categorical feature exploration
5. **Temporal Analysis** - Music evolution trends across decades and eras
6. **Bivariate Analysis** - Feature correlations and relationship mapping
7. **Feature Engineering** - Custom metrics creation (intensity score, emotional positivity, etc.)
8. **Business Insights & Recommendations** - Actionable insights for stakeholders
9. **Results Export** - Cleaned data and analysis summary generation

### 🎯 **Key Discoveries:**

- **Musical Evolution**: Clear trends in audio characteristics over decades
- **Feature Relationships**: Strong correlations between danceability, energy, and popularity
- **Artist Insights**: Identification of most influential and characteristic artists
- **Temporal Patterns**: Era-based music preference shifts and popularity trends

## 🛠️ Technologies & Tools

- **Python 3.13+** with modern data science stack
- **Core Libraries**:
  - `pandas` - Advanced data manipulation and analysis
  - `numpy` - Numerical computing and statistics
  - `seaborn & matplotlib` - Comprehensive data visualization
  - `scipy` - Statistical analysis and hypothesis testing
- **Development Environment**:
  - `Jupyter Notebooks` - Interactive analysis and documentation
  - `uv` - Fast Python package management

## 📁 Project Structure

```
spotify-data-analysis/
├── analysis.ipynb                       # 🔬 Complete EDA notebook with comprehensive analysis
├── spotify_dataset.zip                 # � Raw Spotify tracks dataset (compressed)
├── Presentation - Data Science Insights.pdf  # � Executive summary presentation
├── README.md                           # 📖 Project documentation
└── .venv/                              # 🐍 Virtual environment
```

## 🚀 Quick Start

### Prerequisites

- Python 3.13+ installed
- Git for cloning the repository

### Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Spidy394/spotify-data-analysis.git
cd spotify-data-analysis

# Install required dependencies
pip install pandas numpy matplotlib seaborn scipy jupyter

# Or create a virtual environment (recommended)
python -m venv .venv
.venv\Scripts\activate  # Windows
# source .venv/bin/activate  # macOS/Linux

# Launch Jupyter notebook
jupyter notebook analysis.ipynb
```

## 📈 Analysis Results & Insights

### 🎵 **Musical Evolution Discovered:**

- **Temporal Trends**: Significant shifts in audio characteristics across decades
- **Popularity Patterns**: Modern tracks show higher energy and danceability
- **Feature Correlations**: Strong relationships between danceability, energy, and valence
- **Artist Analytics**: Comprehensive profiling of musical styles and influences

### 💼 **Business Applications:**

- **Streaming Platforms**: Enhanced recommendation algorithms using audio feature relationships
- **Music Producers**: Data-driven insights for creating commercially successful tracks
- **Market Analysis**: Understanding audience preferences across different time periods
- **Content Curation**: Mood and era-based playlist optimization strategies

### 📊 **Key Statistics:**

- **Dataset Size**: Comprehensive multi-decade Spotify tracks collection
- **Features Analyzed**: 15+ audio characteristics and metadata fields
- **Visualizations**: 20+ charts and statistical plots
- **Export Ready**: Cleaned dataset and analysis summary available

## 🔬 Research Applications

This analysis serves as a foundation for:

- **Academic Research** in music information retrieval
- **Industry Consulting** for music streaming services
- **Product Development** for music recommendation systems
- **Educational Purposes** in data science and music analytics

## � Analysis Outputs

After running the complete analysis, you'll get:

- **Comprehensive Visualizations**: 20+ charts showing data distributions, correlations, and trends
- **Statistical Insights**: Descriptive statistics, hypothesis testing results, and correlation analysis
- **Business Recommendations**: Actionable insights for music industry stakeholders
- **Clean Dataset**: Processed data ready for further analysis or modeling

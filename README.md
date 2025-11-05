# Pandas Data Science Learning Journey 📊

A comprehensive learning project focused on mastering pandas for data analysis and building foundational skills in AI and data science.

## 🎯 Project Overview

This repository contains my hands-on learning journey with pandas, NumPy, and data analysis techniques. The project includes practical exercises ranging from basic DataFrame operations to real-world data analysis scenarios.

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.13.7
- Conda/Miniconda

### Environment Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd pandas
   ```

2. **Create conda environment:**
   ```bash
   conda create -n ex00 python=3.13.7 jupyter pandas numpy
   conda activate ex00
   ```

3. **Install required packages:**
   The following packages are installed in the environment:
   - **Core Data Science Stack:**
     - `pandas 2.3.3` - Data manipulation and analysis
     - `numpy 2.3.3` - Numerical computing
     - `jupyter 1.1.1` - Interactive notebooks
   
   - **Supporting Libraries:**
     - `matplotlib-inline` - Plotting in notebooks
     - `ipywidgets` - Interactive widgets
     - `beautifulsoup4` - Web scraping capabilities
     - `requests` - HTTP library for data fetching

4. **Configure environment variables:**
   ```bash
   cp .env.example .env  # Edit as needed
   ```

## 📁 Project Structure

```
pandas/
├── .env                     # Environment configuration
├── =3.9                     # Conda installation log
├── Notebook_ex01.ipynb      # DataFrame basics tutorial
├── Notebook_ex03.ipynb      # E-commerce data analysis
├── .ipynb_checkpoints/      # Jupyter checkpoint files
└── README.md               # This file
```

## 📚 Learning Modules

### 📖 Exercise 01: DataFrame Fundamentals
**File:** `Notebook_ex01.ipynb`

**Topics Covered:**
- Creating DataFrames from NumPy arrays
- Direct DataFrame creation with mixed data types
- Working with custom indices
- Data type inspection and analysis
- Handling object dtype for complex data structures

**Key Skills:**
- Understanding DataFrame structure
- Mixed data type handling
- Index manipulation

### 📊 Exercise 03: E-commerce Data Analysis
**File:** `Notebook_ex03.ipynb`

**Topics Covered:**
- Loading data from remote CSV sources
- Statistical analysis (mean, max, min)
- Data filtering and conditional selection
- String manipulation and parsing
- Aggregation and grouping operations
- Advanced data queries

**Dataset:** E-commerce purchases data (10,000 records, 14 columns)

**Analysis Performed:**
- Purchase price statistics
- Language and job demographics
- Time-based purchase patterns
- Credit card provider analysis
- Email domain analysis
- Data validation and cleaning

**Key Skills:**
- Real-world data analysis
- Statistical computation
- Data filtering and querying
- String operations and parsing
- Business intelligence insights

## 🚀 Getting Started

1. **Activate the environment:**
   ```bash
   conda activate ex00
   ```

2. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

3. **Open any notebook file and start learning!**

## 📈 Learning Objectives

- [ ] Master pandas DataFrame operations
- [ ] Understand data cleaning and preprocessing
- [ ] Learn statistical analysis techniques
- [ ] Practice real-world data analysis scenarios
- [ ] Build foundation for machine learning workflows
- [ ] Develop data visualization skills

## 🎓 Skills Developed

### Technical Skills
- **Data Manipulation:** Filtering, grouping, aggregating data
- **Statistical Analysis:** Descriptive statistics, data summarization
- **Data Cleaning:** Handling missing values, data type conversions
- **String Processing:** Text parsing, pattern matching
- **Data Visualization:** Basic plotting and chart creation

### Analytical Skills
- **Problem Solving:** Breaking down complex data questions
- **Pattern Recognition:** Identifying trends and insights
- **Critical Thinking:** Validating results and assumptions
- **Business Intelligence:** Converting data into actionable insights

## 🔧 Environment Configuration

The `.env` file contains:
- Python path configurations
- Jupyter settings
- Data processing optimizations
- Development environment variables
- Directory structure definitions

## 🤝 Contributing

This is a personal learning project, but feedback and suggestions are welcome! Feel free to:
- Suggest additional exercises
- Recommend datasets for practice
- Share best practices
- Point out improvements

## 📝 Notes

- All notebooks include detailed comments and explanations
- Code follows pandas best practices
- Examples progress from basic to advanced concepts
- Real-world datasets used for practical experience

## 🔗 Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/)
- [Zone01 Kisumu AI Track](https://learn.zone01kisumu.ke/)

---

**Happy Learning!** 🎉

*This project is part of my journey to master data science and AI fundamentals.*

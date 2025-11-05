#  Exploratory Data Analysis on Bitly Public Data

A data exploration project analyzing Bitly’s public dataset to uncover insights about **user activity, time zones, operating systems, and device usage**. The analysis involves cleaning, transforming, and visualizing real-world JSON data to identify behavioral patterns in link-shortening activity.

---

##  Project Overview
This project focuses on exploring and visualizing Bitly’s publicly available data to answer questions such as:
- Which **time zones** are most active?
- What’s the distribution of **Windows vs. non-Windows** users?
- What **devices** are most commonly used for shortened links?

---

##  Tech Stack
- **Python**
- **Pandas** – for data cleaning & manipulation  
- **NumPy** – for numerical operations  
- **Seaborn** – for data visualization  
- **JSON** & **OS** – for loading and processing raw data  

---

##  Steps Performed
1. **Data Loading:** Read and parse Bitly JSON dataset.  
2. **Data Cleaning:** Handle missing or malformed values.  
3. **Exploratory Analysis:** Compute top time zones, devices, and OS distributions.  
4. **Visualization:** Generate plots for time zones, OS usage, and user activity.  
5. **Insights:** Identify regional and platform-based trends in link shortening.  

---

##  How to Run
```bash
# Clone the repository
git clone https://github.com/<your-username>/Exploratory-Data-Analysis-on-Bitly-Public-Data.git
cd Exploratory-Data-Analysis-on-Bitly-Public-Data

# Install dependencies
pip install pandas numpy seaborn

# Open the notebook
jupyter notebook Work.ipynb
```

---

##  Key Insights
- Most active time zones correspond to U.S. regions.  
- Windows users form a significant portion of the dataset.  
- Visualizations highlight clear temporal and platform-based trends.  

---

##  Acknowledgments
- **Dataset:** Bitly Public Data (from *Python for Data Analysis* by Wes McKinney)  
- **Tools:** Jupyter Notebook, Pandas, Seaborn


# 📚 Amazon Best-Selling Books Analysis (2009–2019)

This project performs an in-depth Exploratory Data Analysis (EDA) on **Amazon’s Best-Selling Books** dataset. The goal is to uncover patterns related to ratings, reviews, pricing, yearly trends, genre comparisons, and author popularity using Python-based data analysis and visualization techniques.


## 📂 Dataset Information
- **Rows:** 550  
- **Columns:** 7  
- **Features:**  
  - Book Name  
  - Author  
  - User Rating  
  - Reviews  
  - Price  
  - Year  
  - Genre (Fiction / Non-Fiction)  
- **Missing Values:** None  

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Plotly  
- WordCloud  
- Missingno  

## 🔍 Project Workflow

### ✔️ 1. Data Loading & Inspection  
- Loaded the dataset using Pandas  
- Verified data types, dimensions, column distributions  
- Confirmed there are **no missing values**

### ✔️ 2. Exploratory Data Analysis  
- Distribution of **User Ratings** and **Price**  
- Top books with the **highest reviews**  
- Checked duplicates in book titles  
- Compared Fiction vs Non-Fiction patterns

### ✔️ 3. Visualization Insights  
- **Histograms** for Ratings & Price  
- **Scatter plots** to analyze:
  - Rating vs Reviews  
  - Rating vs Price  
  - Genre-wise relationships  

- **Line charts** for:
  - Year-wise Reviews trend  
  - Year-wise Price trend  

- **WordClouds** for Authors:
  - Fiction Authors  
  - Non-Fiction Authors  

- **Interactive Plotly Visualizations**
  - Top 10 best-selling authors  
  - Author-wise rating & review comparison  

### ✔️ 4. Genre-Level Segmentation
Separated the dataset into:
- **Fiction**
- **Non-Fiction**

Analyzed:
- Ratings  
- Reviews  
- Top books  
- WordClouds per genre  


## 📊 Key Insights
- Best-sellers consistently maintain **ratings between 4.5 and 4.9**  
- **Fiction books** receive significantly higher reviews than Non-Fiction  
- Price does **not strongly influence** user ratings  
- Certain authors (Jeff Kinney, Suzanne Collins, Rick Riordan) dominate the best-seller charts  
- Review count is a more powerful popularity indicator than ratings  


## 🧠 Summary
This project delivers a complete end-to-end analysis of Amazon’s bestselling books, highlighting patterns that influence a book’s commercial success. By combining data exploration, visualization, segmentation, and author analysis, it provides valuable insights into long-term trends in the publishing industry.

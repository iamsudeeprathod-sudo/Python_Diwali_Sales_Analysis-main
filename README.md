🪔 Diwali Sales Data Analysis
Turning festive shopping data into meaningful business insights with Python
A beginner-friendly Exploratory Data Analysis (EDA) project that studies customer purchasing patterns during Diwali to understand buyer behaviour, sales trends, and popular product categories.

 Project Overview
This project explores Diwali sales data to identify customer segments and purchasing trends. Using Python libraries, the dataset is cleaned, analysed, and visualised to highlight patterns across gender, age group, state, marital status, occupation, and product category.

The objective is to practise a real-world data analytics workflow and demonstrate how exploratory analysis can support business understanding and decision-making.
🎯 Project Objectives
Clean and prepare raw sales data for analysis.
 Inspect missing values and remove incomplete records.
 Explore customer demographics and purchasing behaviour.
 Compare sales and order patterns across states and customer groups.
 Identify popular product categories and frequently ordered products.
 Communicate findings through clear visualisations.

🧰 Tools & Technologies
Tool / Library	Purpose
Python	Data analysis and scripting
Jupyter Notebook	Interactive analysis
Pandas	Data loading, cleaning, grouping, and analysis
NumPy	Numerical operations
Matplotlib	Data visualisation
Seaborn	Statistical charts and visual exploration


📂 Repository Structure
Diwali-Sales-Analysis/
│
├── Diwali_Sales_Analysis.ipynb   # Main analysis notebook
├── Diwali Sales Data.csv         # Dataset
└── README.md                     # Project documentation
📊 Dataset Details
The supplied dataset contains 11,251 records and 13 columns before the cleaning steps in the notebook.

  Important fields include:
 User_ID – Customer identifier
 Cust_name – Customer name
 Product_ID – Product identifier
 Gender – Customer gender
 Age and Age Group – Customer age information
 Marital_Status – Marital status
 State and Zone – Customer location
 Occupation – Customer occupation
 Product_Category – Product category
 Orders – Number of orders
 Amount – Purchase amount
  
⚙️ Project Workflow
1. Import libraries – Load Pandas, NumPy, Matplotlib, and Seaborn.
2. Load the dataset – Read the CSV file into a Pandas DataFrame.
3. Understand the data – Inspect the shape, first records, data types, and descriptive statistics.
4. Clean the data – Remove the Status and unnamed1 columns, check missing values, drop rows containing missing values, and convert Amount to an integer.
5. Explore the data – Analyse customer and sales patterns using grouping and aggregation.
6. Visualise insights – Create charts to compare customer segments, locations, occupations, and products.

🔍 Key Analysis & Findings
The notebook explores the following areas:
Analysis Area	What the notebook examines
Gender	Buyer count and total purchase amount by gender
Age Group	Sales amount across age groups
State	Top 10 states by order count and sales amount
Marital Status	Purchase amount by marital status and gender
Occupation	Sales amount across occupation groups
Product Category	Top product categories by sales amount
Product ID	Products with the highest number of orders


Highlights recorded in the notebook
- Female customers account for more buyers and higher purchasing power in the analysed data.
- The 26–35 age group is highlighted as a major buyer segment, particularly women.
- Uttar Pradesh, Maharashtra, and Karnataka are highlighted among the leading states for orders and sales.
- Married women are identified as a strong purchasing segment in the analysis.
- IT, Healthcare, and Aviation appear among the occupations associated with higher purchases.
- Food, Clothing, and Electronics are highlighted among the leading product categories.
These are observations from this dataset and analysis, not universal conclusions about all customers or sales periods.

▶️ How to Run This Project
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/Diwali-Sales-Analysis.git
2. Open the project folder
cd Diwali-Sales-Analysis
3. Install the required libraries
pip install pandas numpy matplotlib seaborn jupyter
4. Launch Jupyter Notebook
5. jupyter notebook
6. Run the notebook
Open Diwali_Sales_Analysis.ipynb and run the cells from top to bottom.

Make sure Diwali Sales Data.csv is in the same folder as the notebook.
 Skills Demonstrated
 Data loading and inspection
 Data cleaning and missing-value handling
 Data type conversion
 Exploratory Data Analysis (EDA)
 Grouping and aggregation with Pandas
 Customer segmentation
 Data visualisation
 Communicating data-driven observations

🚀 Future Improvements
 Add an interactive dashboard using Power BI or Plotly.
 Explore customer-level spending and order frequency in more depth.
 Add reusable analysis functions and a reproducible environment file.
 Compare findings across additional sales periods, if data becomes available.

 👨‍💻 Author
  Sudeep Rathod
  
  Aspiring Data Analyst | Python | SQL | Excel | Power BI
  GitHub: https://github.com/iamsudeeprathod-sudo/Python_Diwali_Sales_Analysis-main.git
  LinkedIn: www.linkedin.com/in/sudeep-rathod-223750398 
  Support
If you find this project useful for learning data analytics, consider giving the repository a star ⭐.
<div align="center">Thank you for visiting this project!

Learning • Analysing • Improving
</div>

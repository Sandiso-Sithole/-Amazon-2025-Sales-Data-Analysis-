 Amazon Sales Data Analysis – 2025 (Mock Dataset from Kaggle)

Project Objective
Analyze mock Amazon sales data from 2025 to uncover trends, identify high-performing products and cities, and derive actionable insights that can support future sales strategies and business decisions.

Tools & Technologies Used
Python (Pandas, NumPy)

Data Visualization: Matplotlib, Seaborn

Jupyter Notebook for interactive analysis

Power BI (optional extension for dashboards)

Microsoft Excel (initial data view and exploration)

Dataset Overview
Cleaned dataset contains the following key columns:

Order ID

Date (converted to datetime64[ns])

Product, Category, Customer Name, Customer Location

Price, Quantity, Total Sales, Revenue per Item

Payment Method, Status, Month

Key Questions Explored
Which month had the highest sales?

What products performed best during that month?

Which city placed the most orders?

Which product was most purchased and by which city?

What trends can help boost future sales?

Key Insights
Top Product: Smartwatch was the most sold overall.

Top City: February placed the most orders — possibly influenced by demographic/economic factors.

Top Month: March generated the highest revenue.

 BestSelling Categories and Preferred Payment Methods were also identified to inform marketing focus.

 Data Cleaning Steps
Converted Date to datetime format

Casted categorical fields to optimize performance

Added Month and Revenue per Item columns

Handled missing/duplicate data (if any)

Future Improvements
Integrate real-time data from APIs or AWS S3

Deploy as interactive dashboard with Streamlit or Power BI

Predict sales trends using regression models

How to Use:
Clone the repo

Open Amazon 2025 Sales mock stat.ipynb in Jupyter Notebook

Run the cells to reproduce the analysis and visuals


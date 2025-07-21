# Chrisantine Carelle Profeta - Data-Analysis-Project

👋 Hi! I'm Chrisantine Carelle Profeta, an aspiring data analyst with hands-on experience in Excel, Power BI, SQL, Tableau, and Python. This portfolio showcases some of the projects I’ve worked on while learning and applying real-world data analysis techniques.

---

## 📑 Table of Contents

### Portfolio Projects

#### 📊 Structured Data Analysis

- **Excel**
  - [Credit Card Risk Analysis](https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Credit_Card_Analysis.xlsx)
  - [Superstore Sales Performance Analysis](https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Superstore_Analysis.xlsx)
  - [Customer Satisfaction Analysis](https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Customer_Analysis.xlsx)

- **Power BI**
  
- **SQL**
  
- **Tableau**
  
---

## 📁 Project Details

### Credit Card Risk Analysis

**File:** [Credit_Card_Risk_Analysis.xlsx](https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Credit_Card_Analysis.xlsx)

**Dataset:** [Credit Card Customers (Kaggle)](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

**🎯 Goal:**  
To group customers based on how they use their credit and help the business understand who might be a risk.

**📝 Description:**  
- Cleaned data using Power Query by removing duplicates, blanks, and errors;
- Created additional columns to categorize and sort data: `Age Group` for age ranges; `Income Sort Key` and `Age Sort Key` to enable accurate sorting in visualizations; `Credit Risk Level` based on the percentage of remaining credit, used to classify customers as Low, Medium, or High risk.
- Used the formula `(Avg_Open_To_Buy / Credit_Limit) * 100` to calculate the percentage of remaining credit—this helps classify customers into risk levels based on how much credit they have left:
  - Low Risk = ≥ 75% 
  - Medium Risk = 26% to 74%  
  - High Risk = ≤ 25%

**🧠 Skills:**  
Data transformation and Data categorization

**🛠️ Technology:**  
Microsoft Excel (Power Query, Pivot Table)

**✅ Result:**  
The analysis showed which customers are high, medium, or low risk based on how much credit they have left. This helps the business make better decisions and focus on the right customers.

<img src="https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Project%20Visuals/Credit_Card_Visual.png" />

### Superstore Sales Performance Analysis

**File:** [Superstore_Analysis.xlsx]( https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Superstore_Analysis.xlsx)

**Dataset:** [Sales Forecasting Dataset (Kaggle)](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

**🎯 Goal:**  
To analyze sales performance across different states and make it easy to explore sales trends using a clean and interactive dashboard.

**📝 Description:**  
- Cleaned data using Power Query by removing duplicates, blanks, and errors; added columns for `Shipping Duration` (Ship Date - Order Date), and extracted `Year` and `Month` from Order Date.
- Used the formula `=IF(M3="", "", M3)` to ensure the map chart only displays values when data is present—this helps prevent blank or error cells from appearing on the visualization.
- Built a Total Sales by State table and connected it to a map chart for visual geographic insights.
- Created a dynamic dashboard using Pivot Tables and Slicers for interactive analysis.

**🧠 Skills:**  
Data cleaning and data visualization

**🛠️ Technology:**  
Microsoft Excel (Power Query, Pivot Table, Slicers)

**✅ Result:**  
The dashboard showed total sales by state, shipping times, and trends by year and month. This helped give a clear view of where sales are strong and where improvements can be made.

<img src="https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Project%20Visuals/Superstore_Visual.png" />

### Customer Satisfaction Analysis

**File:** [Customer_Analysis.xlsx](https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Customer_Analysis.xlsx)

**Dataset:** [Airline Passenger Satisfaction Dataset (Kaggle)](https://www.kaggle.com/datasets/raminhuseyn/airline-customer-satisfaction)

**🎯 Goal:**  
To analyze passenger satisfaction in the airline industry and provide clear, interactive insights based on customer types, travel class, age group, and service quality.

**📝 Description:**  
- Cleaned the dataset using Power Query, removing duplicates and validating data integrity.
- Added a new column to categorize passengers into `Age Group` (Children, Adult, Elderly).
- Created a dynamic heatmap using conditional formatting to highlight rating frequencies per service type (red = lowest, green = highest).
- Integrated slicers (Customer Type, Travel Type, Class) for interactive filtering and exploration.
- Uses cards to display key metrics such as Average Flight Distance, Departure Delay, and Arrival Delay.

**🧠 Skills:**  
Data cleaning and data visualization

**🛠️ Technology:**  
Microsoft Excel (Power Query, Pivot Table, Slicers, Conditional Formatting)

**✅ Result:**  
The dashboard offers a user-friendly overview of passenger satisfaction across multiple variables. Key metrics and visuals make it easy to identify areas needing service improvement (e.g., food and drink, legroom service) and understand which factors contribute to high satisfaction among loyal customers and business travelers.

<img src="https://github.com/CarelleProfeta/Data-Analysis-Project/blob/master/Structured%20Data/Excel/Project%20Visuals/Customer_Visual.png" />

---

## 📌 Disclaimer
The datasets used in this project are for educational and portfolio purposes only. All insights and visuals are created for learning and demonstration.

---

Feel free to connect with me if you're interested in data analytics, feedback, or collaboration opportunities!

# Customer Segmentation Using RFM Analysis in E-Commerce

## 📌 Project Overview
This project applies **RFM (Recency, Frequency, Monetary) analysis** to an e-commerce dataset to segment customers based on their purchasing behavior. The goal is to identify **high-value customers, at-risk segments, and optimize marketing strategies** using data-driven insights.

## 🛠️ Tools & Technologies Used
- **Python** 🐍 (Data analysis, RFM calculations)
- **Jupyter Notebook** 📓 (Exploratory analysis, data processing)
- **Pandas, Matplotlib, Seaborn** 📊 (Data manipulation & visualization)
- **Power BI** 📈 (Dashboard creation & insights visualization)
- **Git & GitHub** 🗂️ (Version control, repository management)

## 📂 Dataset 
### Source
- The dataset is sourced from **[UC Irvine ML Repository's Online Retail Dataset](http://archive.ics.uci.edu/dataset/352/online+retail)**.  
- It is licensed under **CC BY 4.0**, allowing modifications and redistribution with attribution.  
- Citation: *Chen, D. (2015). Online Retail Dataset. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.*.  

### Details
- This is a **transactional dataset** which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.
- Key columns include **Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country**.
- The data is cleaned and preprocessed before performing RFM analysis.

## 🛠 Methodology
1. **Data Preprocessing**:
   - Handling missing values, duplicates, and formatting date fields.
   - Removing non-product stockcodes and cancelled orders.
3. **RFM Score Calculation**:
   - **Recency (R)**: Days since last purchase.
   - **Frequency (F)**: Number of purchases made.
   - **Monetary (M)**: Total amount spent.
4. **Customer Segmentation**: Assigning RFM scores and categorizing customers into segments.
5. **Pareto Principle Application**:
   - Identifying that **27% of customers contribute to 80% of sales**.
   - Identifying that **21% of products contribute to 80% of sales**.
7. **Dashboard Creation**: Visualizing insights with plots and charts.

## 📊 Visualizations & Dashboard
- **Analyzing Customer Trends**: Patterns and Insights Over Time.
- **Heatmap**: Correlation between R, F, and M scores.
- **Customer Segmentation**: Distribution of customer groups.
- **Dashboard**: Interactive representation of key insights.

## 📡 Presentation
You can view the project presentation [here](https://docs.google.com/presentation/d/1arzQM6laZkMrgpH-SlHPTw-W7XPREIyX7IpMVmCO_As/edit?usp=sharing).

## 📌 Key Insights
- A small percentage of customers contribute to the majority of sales (Pareto 80/20 Rule).
- High-value customers can be **targeted with personalized offers** to increase retention.
- At-risk customers can be **re-engaged with special incentives**.

## 💡 Future Improvements
- **Implement machine learning for customer segmentation** to enhance the accuracy of grouping customers.
- **Analyze cancelled orders** to gain deeper insights into customer dissatisfaction and potential improvements.
- **Expand segmentation using demographic and behavioral data** for more personalized marketing strategies.

## 📝 Author
👤 **Reet Chandra**  
📧 reetphy@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/reet-chandra/)  

## ⭐ Contributing
Feel free to open issues or submit pull requests to improve this project!

## 📜 License
This project is licensed under the **Creative Commons (CC BY 4.0)**.

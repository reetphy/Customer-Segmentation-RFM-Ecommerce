# Customer Segmentation Using RFM Analysis in E-Commerce

## 📌 Project Overview
This project applies **RFM (Recency, Frequency, Monetary) analysis** to an e-commerce dataset to segment customers based on their purchasing behavior. The goal is to identify **high-value customers, at-risk segments, and optimize marketing strategies** using data-driven insights.

## 📂 Dataset 
### Source
- The dataset is sourced from **[UC Irvine ML Repository's Online Retail Dataset](http://archive.ics.uci.edu/dataset/352/online+retail)**.  
- It is licensed under **CC BY 4.0**, allowing modifications and redistribution with attribution.  
- Citation: *Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.*.  

### Details
- This is a **transactional data** set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.
- Key columns include **Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country**.
- The data is cleaned and preprocessed before performing RFM analysis.

## 🛠 Methodology
1. **Data Preprocessing**: Handling missing values, duplicates, and formatting date fields.
2. **RFM Score Calculation**:
   - **Recency (R)**: Days since last purchase.
   - **Frequency (F)**: Number of purchases made.
   - **Monetary (M)**: Total amount spent.
3. **Customer Segmentation**: Assigning RFM scores and categorizing customers into segments.
4. **Pareto Principle Application**: Identifying that **27% of customers contribute to 80% of sales**.
5. **Dashboard Creation**: Visualizing insights with plots and charts.

## 📊 Visualizations & Dashboard
- **Pareto Chart**: Showing the contribution of top customers.
- **Heatmap**: Correlation between R, F, and M scores.
- **Customer Segmentation**: Distribution of customer groups.
- **Dashboard**: Interactive representation of key insights.

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-rfm.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python rfm_analysis.py
   ```
4. Open the dashboard (if applicable):
   ```bash
   streamlit run dashboard.py
   ```

## 📌 Key Insights
- A small percentage of customers contribute to the majority of sales (Pareto 80/20 Rule).
- High-value customers can be **targeted with personalized offers** to increase retention.
- At-risk customers can be **re-engaged with special incentives**.

## 💡 Future Improvements
- Incorporate **predictive modeling** for customer churn.
- Implement **automated alerts** for high-risk customers.
- Expand segmentation using **demographic and behavioral data**.

## 📝 Author
👤 **Your Name**  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  

## ⭐ Contributing
Feel free to open issues or submit pull requests to improve this project!

## 📜 License
This project is licensed under the **MIT License**.

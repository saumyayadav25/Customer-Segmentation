# 🛍️ Mall Customer Segmentation Project

## 📌 Project Overview
This project uses **K-Means Clustering** to segment mall customers based on their **Annual Income** and **Spending Score**.  
The goal is to identify **distinct customer groups** to help businesses **personalize marketing strategies**, **optimize resources**, and **increase revenue**.

---

## 🔹 Key Use Cases
- Targeted marketing campaigns for different customer segments
- Price optimization and product recommendations
- Customer acquisition & retention strategies

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## 🧾 Dataset Information  

**Dataset Name:** `Mall_Customers.csv`  
**Total Entries:** 200  

| Column | Description |
|--------|--------------|
| `CustomerID` | Unique ID assigned to each customer |
| `Gender` | Male or Female |
| `Age` | Customer’s age |
| `Annual Income (k$)` | Annual income in thousand dollars |
| `Spending Score (1–100)` | Score assigned based on customer’s behavior and spending nature |


## Project Highlights
- **Dataset:** 200 mall customers with features: Age, Gender, Annual Income, Spending Score  
- **Clustering Algorithm:** K-Means  
- **Optimal Clusters:** 5 (determined using Elbow Method)  

## 📊 Cluster Analysis

### 🟢 **Cluster 1 – Moderate Income, Average Spenders**
- Customers with **medium annual income** and **average spending behavior**.  
- Represent the **core customer base**.  
- **Marketing Strategy:** Maintain engagement via loyalty programs and regular offers.

---

### 🔴 **Cluster 2 – High Income, High Spenders**
- Customers with **high income** and **high spending scores**.  
- Represent the **premium / luxury segment**.  
- **Marketing Strategy:** Offer exclusive deals, VIP experiences, and personalized recommendations.

---

### 🟡 **Cluster 3 – High Income, Low Spenders**
- Customers with **high income** but **low spending scores**.  
- May not find current offerings appealing or are **price-conscious**.  
- **Marketing Strategy:** Introduce new premium products or targeted campaigns to increase spending.

---

### 🟣 **Cluster 4 – Low Income, Low Spenders**
- Customers with **low income** and **low spending scores**.  
- Represent the **budget-conscious** group.  
- **Marketing Strategy:** Focus on discounts, value-for-money bundles, or entry-level offers.

---

### 🔵 **Cluster 5 – Low Income, High Spenders**
- Customers with **low income** but **high spending scores**.  
- Possibly **young or trend-driven** customers who spend beyond their means.  
- **Marketing Strategy:** Promote affordable luxury and frequent small purchase opportunities.

---

## 🚀 How to Use
1. Clone the repo:
```bash
git clone https://github.com/saumyayadav25/Mall-Customer-Segmentation.git
cd Mall-Customer-Segmentation
```

2. Install dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Run the project:
```bash
python customer_segmentation.py
```

# 📈 Insights

- 5 distinct customer segments identified

- High-value segments: High-income high spenders & low-income trend-driven spenders

- Opportunity for targeted campaigns and increasing revenue

# 💡 Future Enhancements

- Include Age & Gender for more granular segmentation

- Deploy an interactive web app to predict cluster for new customers

- Compare K-Means with Hierarchical or DBSCAN clustering

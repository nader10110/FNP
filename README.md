# 📊 Data Analysis Project – Ferns and Petals (India)

## 📝 Project Overview  
This project analyzes sales data for **Ferns and Petals (FNP)**, an Indian company that sells gifts online for all occasions.  
The main goal of the project is to help the company:  
- Increase overall **revenue**  
- Better understand their **customers**  
- Identify **best-selling products**  
- Find the **top-performing cities**  

---

## 📂 Dataset Used  
- **customers.csv** → Customer details  
- **orders.csv** → Order transactions (Order Date, Delivery Date, Price, Quantity, City, etc.)  
- **products.csv** → Product information (Category, Product Name, etc.)  

---

## 🔧 Steps Performed  

### 1️⃣ Data Cleaning & Transformation (Power Query)  
- Removed duplicates and null values  
- Corrected data types (dates, numbers, text)  
- Created calculated columns:  
  - **Revenue = Price × Quantity**  
  - **Delivery Days = Delivery_Date - Order_Date**  
  - Extracted **Month, Hour** for time-based analysis  

### 2️⃣ Data Modeling  
- Established relationships between:  
  - Customers ↔ Orders  
  - Products ↔ Orders  

### 3️⃣ Business KPIs  
- **Total Revenue**  
- **Average Delivery Time**  
- **Top Products by Sales**  
- **Sales Trends by Month**  
- **Customer Spending Patterns**  

### 4️⃣ Visual Analysis (Excel)  
- Pivot Tables & Pivot Charts  
- Interactive Slicers for filtering  
- Trend analysis and comparison  

---

## 📈 Key Insights  
- ✅ Identified **top revenue-generating products**  
- ✅ Found **highest sales cities**  
- ✅ Tracked **monthly sales trends**  
- ✅ Analyzed **customer purchase behavior**  

---

## 🛠 Tools Used  
- **Microsoft Excel**  
  - Power Query  
  - Pivot Tables & Charts  
  - Slicers  
- **Data Modeling Techniques**  

---

## 🚀 Future Improvements  
- Build an interactive **Power BI Dashboard**  
- Implement advanced **predictive analytics**  
- Compare **seasonal vs. non-seasonal sales**

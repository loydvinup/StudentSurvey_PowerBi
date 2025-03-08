# Power BI Student Survey Analysis - Retail Store  

## **Overview**  
This Power BI report analyzes **student spending habits** in various retail stores across different **store locations and settings** (Urban, Suburban, Rural). The dataset provides insights into **spending on video games, sports, toys, books, gadgets, and more**.  

## **Dataset Details**  
📂 **Dataset Name:** Student Survey  
📊 **Industry:** Retail Store  
🔢 **Key Features:**  
- **Store Location** – Where the store is situated  
- **Store Setting** – Type of store (Urban, Suburban, Rural)  
- **Age** – Age of students surveyed  
- **Category-wise Purchases** – Spending on video games, indoor games, outdoor sports, toys, books, gadgets, etc.  
- **Total Amount of Purchase (TAP)** – Overall amount spent by students  

---

## **Power BI Report Structure**  

### **1️⃣ Tabular Visualization**  
✅ **Conditional Formatting on Total Amount of Purchase (TAP)**  
- **Red** 🟥 for TAP **< 35,000**  
- **Yellow** 🟨 for TAP **35,000 - 59,999**  
- **Blue** 🟦 for TAP **≥ 60,000**  

### **2️⃣ Matrix Visualization**  
✅ **Displays outdoor sports spending** across **ages and store settings**  
✅ **Conditional Formatting** applied for total outdoor sports spending  

### **3️⃣ Funnel Chart**  
✅ **Shows TAP by Store Setting** with **data labels as a percentage of the first category**  

### **4️⃣ Pie Chart**  
✅ **Displays TAP by Store Location**  
✅ **Filtered for Suburban Store Setting Only**  

### **5️⃣ Advanced Visualizations**  
✅ **Scatter Plot:** Video games vs. Outdoor sports spending across different ages  
✅ **Sand Dance Plot:** Indoor sports vs. Video games spending across age groups  

### **6️⃣ Data Access Restriction**  
✅ **User Mapping Applied:**  
- **Mani** can view only **Rural data** (not Urban or Suburban)  
- Other users are restricted based on access permissions  

### **7️⃣ Power BI Cloud Service Publishing**  
✅ **Published Dashboard Includes:**  
- Funnel Chart  
- Scatter Plots  

✅ **Scheduled Refresh:** Every **4 hours, 6 times a day**  

### **8️⃣ Power BI Q&A Feature**  
✅ **"What is the average age of students?"** – Displays the result  
✅ **Donut Chart for TAP by Store Location**  

---

## **Technologies Used**  
🚀 **Power BI Desktop & Power BI Cloud Service**  
📊 **DAX (Data Analysis Expressions)**  
📈 **Power Query for Data Cleaning**  

---

## **Results & Insights**  
- **TAP is highest in Urban stores** due to higher spending on gadgets & video games  
- **Outdoor sports spending is higher among younger age groups**  
- **Suburban stores have a balanced spending pattern across all categories**  
- **Conditional formatting helps in better readability of spending trends**  

---

## **Future Improvements**  
🔹 Implement **predictive analytics** to forecast student spending trends  
🔹 Add **custom visuals** for better interactivity  
🔹 Integrate **external sales data** for deeper business insights  

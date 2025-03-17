# 🎯 V Mart Apparel Sales Analysis Project  

## 📌 Overview  

This project analyzes **transactional sales data** from **V Mart**, a value retail chain in India, to identify key product attributes and sales trends. The goal is to provide **data-driven recommendations** for:  

✅ Improved **inventory management**  
✅ Enhanced **marketing strategies**  
✅ Increased **profitability**  

The analysis focuses on **apparel sales data** for **May, June, and July**.  

---

## 📂 Project Structure  

```plaintext
📦 Project Directory  
├── 📄 README.md  
│  
├── 📂 Codes  *(Analysis Notebooks)*  
│   ├── 📄 csvCreationForGraphing.ipynb  
│   ├── 📄 EDA_columns_understanding.ipynb  
│   ├── 📄 JulyAnalysis.ipynb  
│   ├── 📄 JuneAnalysis.ipynb  
│   ├── 📄 MayAnalysis.ipynb  
│   ├── 📄 monthWiseDfCreation.ipynb  
│  
└── 📂 submissionFile  *(Level-wise submission documents)*  
    ├── 📄 Mid Term.pdf  
    ├── 📄 Proposal.pdf  
```

---

## 📊 Data Sources  

📌 **Dataset:** Transactional sales data from V Mart's billing counters.  

🔹 **Key Attributes:**  
- 🏷 **Product Category:** `GRPNAME`, `LEV1GRPNAME`, `LEV2GRPNAME`  
- 🔢 **SKU-level Details:** `ARTICLECODE`, `ARTICLENAME`, `ICODE`, `CNAME2`, `CNAME3`, `CNAME6`, `DESC3`  
- 💰 **Sales Metrics:** `GROSSAMT`, `NETAMT`, `QTY`, `DISCOUNTAMT`, `PROMOAMT`  
- 👥 **Customer Demographics:** `LEV1GRPNAME`, `LEV2GRPNAME`  
- 🏬 **Store Information:** `UDFSTRING15`, `OPH3`, `SHRTNAME`, `ADM_SITE_CODE`  

📅 **Timeframe:** May, June, and July  
📄 **Format:** Parquet  

---

## 🛠 Tools & Technologies  

🔹 **Programming Language:** Python  
🔹 **Data Analysis Libraries:** `Pandas`, `NumPy`  
🔹 **Visualization Tools:** `Matplotlib`, `Seaborn`  
🔹 **Development Environment:** Jupyter Notebook  
🔹 **Additional Tools:** Google Sheets (for preliminary analysis)  

---

## 🔍 Key Analysis Steps  

### 1️⃣ **Data Loading & Preprocessing**  
✔ Load data from Parquet files into Pandas DataFrames  
✔ Convert date formats  
✔ Handle missing values  
✔ Address inconsistencies (e.g., negative quantities)  

### 2️⃣ **Exploratory Data Analysis (EDA)**  
✔ Compute descriptive statistics (mean, median, standard deviation)  
✔ Analyze data distributions  
✔ Identify potential outliers  

### 3️⃣ **Sales Trend Analysis**  
✔ Month-on-Month (MoM) sales comparisons  
✔ Same-Week MoM analysis for seasonality  

### 4️⃣ **Attribute Importance Assessment**  
✔ Identify top-performing attribute combinations in each apparel category  

### 5️⃣ **Correlation Analysis**  
✔ Examine relationships between product attributes and sales performance  

### 6️⃣ **Visualization**  
✔ Create charts and graphs for better insights  

---

## 📈 Findings & Recommendations  

### 📊 **Key Sales Insights**  
🔹 **June** recorded the highest sales, likely due to promotions  
🔹 **Men's apparel** consistently leads in sales  
🔹 **Solid colors & durable fabrics** perform well in menswear  
🔹 **Printed designs** are most popular in children's wear  
🔹 **DESI MIX** is the dominant brand in Women's Ethnic wear  
🔹 **Sales in Boys and Girls categories declined in July**  

### 🎯 **Recommendations for V Mart**  
✅ Optimize **inventory** based on top-performing brands and styles  
✅ Align stock with **seasonal trends**  
✅ Investigate and address **declining sales** in Boys & Girls categories  
✅ Focus **promotions during peak weeks**  
✅ Leverage **brand recognition** in marketing campaigns  
✅ Implement **data-driven discount strategies**  
✅ Avoid excessive discounting to protect **profit margins**  

---

## 🚀 Future Work  

🔹 Deep-dive into **attribute relationships** to predict sales trends  
🔹 Develop **predictive models** for demand forecasting  
🔹 Optimize **promotional spending** using machine learning  
🔹 Implement **personalized product recommendations**  
🔹 Expand analysis to **other data sources** (customer demographics, marketing campaign data)  

---

## 🏷 Roll Number  

👤 **Tanmay Garg** (22f2001630)  

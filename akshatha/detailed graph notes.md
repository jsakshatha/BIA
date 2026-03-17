# 📊 Power BI Charts – Superstore Teaching Guide

---

## 🔑 Common Columns in Superstore

- **📂 Categorical (Axis / Legend)**  
  Category, Sub-Category, Segment, Region, State, Ship Mode  

- **🔢 Numerical (Values)**  
  Sales, Profit, Quantity, Discount  

---

# 1️⃣ 📊 Stacked Column Chart

## 🎯 Objective  
👉 Compare **multiple categories + contribution (parts of total)**  

## 🧭 Axis Selection  
- **X-axis (Categorical)** → Category / Region  
- **Y-axis (Numerical)** → Sales / Profit  
- **Legend (Categorical)** → Segment / Sub-Category  

## 📌 Examples  

### ✅ Example 1  
- X-axis → Category  
- Y-axis → Sales  
- Legend → Segment  

👉 Shows: Which segment contributes more sales in each category  

### ✅ Example 2  
- X-axis → Region  
- Y-axis → Profit  
- Legend → Category  

👉 Shows: Profit distribution across regions  

---

# 2️⃣ 🥧 Pie Chart  

## 🎯 Objective  
👉 Show **percentage contribution of parts to whole**  

## 🧭 Axis Selection  
- **Legend (Categorical)** → Category / Segment  
- **Values (Numerical)** → Sales / Profit  

## 📌 Examples  

### ✅ Example 1  
- Legend → Category  
- Values → Sales  

👉 Shows: Category-wise sales share  

### ✅ Example 2  
- Legend → Segment  
- Values → Profit  

👉 Shows: Segment-wise profit share  

---

# 3️⃣ 📈 Line Chart  

## 🎯 Objective  
👉 Show **trend over time**  

## 🧭 Axis Selection  
- **X-axis (Time)** → Order Date  
- **Y-axis (Numerical)** → Sales / Profit  

## 📌 Examples  

### ✅ Example 1  
- X-axis → Month  
- Y-axis → Sales  

👉 Shows: Monthly sales trend  

### ✅ Example 2  
- X-axis → Year  
- Y-axis → Profit  

👉 Shows: Yearly profit trend  

---

# 4️⃣ 🍩 Donut Chart  

## 🎯 Objective  
👉 Show **proportion (better visual than pie)**  

## 🧭 Axis Selection  
- **Legend (Categorical)** → Region / Category  
- **Values (Numerical)** → Sales / Quantity  

## 📌 Examples  

### ✅ Example 1  
- Legend → Region  
- Values → Sales  

👉 Shows: Region-wise sales share  

### ✅ Example 2  
- Legend → Category  
- Values → Quantity  

👉 Shows: Quantity distribution  

---

# 5️⃣ 🔻 Funnel Chart  

## 🎯 Objective  
👉 Show **stages or top-down filtering**  

## 🧭 Axis Selection  
- **Category** → Category / Sub-Category  
- **Values** → Sales / Quantity  

## 📌 Examples  

### ✅ Example 1  
- Category → Category  
- Values → Sales  

👉 Shows: Top categories by sales  

### ✅ Example 2  
- Category → Sub-Category  
- Values → Quantity  

👉 Shows: Most sold sub-categories  

---

# 6️⃣ 📟 KPI Card  

## 🎯 Objective  
👉 Show **single important metric**  

## 🧭 Fields  
- **Indicator** → Sales / Profit  
- **Trend Axis** → Date  

## 📌 Examples  

### ✅ Example 1  
- Indicator → Total Sales  

👉 Shows: Overall sales  

### ✅ Example 2  
- Indicator → Profit  
- Trend → Date  

👉 Shows: Profit performance  

---

# 7️⃣ 🎀 Ribbon Chart  

## 🎯 Objective  
👉 Show **ranking changes over time**  

## 🧭 Axis Selection  
- **X-axis** → Date  
- **Y-axis** → Sales / Profit  
- **Legend** → Category / Region  

## 📌 Examples  

### ✅ Example 1  
- X-axis → Year  
- Y-axis → Sales  
- Legend → Category  

👉 Shows: Top category each year  

### ✅ Example 2  
- X-axis → Month  
- Y-axis → Profit  
- Legend → Region  

👉 Shows: Region ranking over time  

---

# 8️⃣ 🌳 Tree Map  

## 🎯 Objective  
👉 Show **hierarchical data with size comparison**  

## 🧭 Fields  
- **Category** → Category / Sub-Category  
- **Values** → Sales / Profit  

## 📌 Examples  

### ✅ Example 1  
- Category → Category  
- Values → Sales  

👉 Shows: Category contribution size  

### ✅ Example 2  
- Category → Sub-Category  
- Values → Profit  

👉 Shows: Profit distribution  

---

# 9️⃣ 🗺️ Map Chart  

## 🎯 Objective  
👉 Show **geographical data**  

## 🧭 Fields  
- **Location** → State / City / Region  
- **Values** → Sales / Profit  

## 📌 Examples  

### ✅ Example 1  
- Location → State  
- Values → Sales  

👉 Shows: Sales by state  

### ✅ Example 2  
- Location → Region  
- Values → Profit  

👉 Shows: Profit by region  

---

# 🔟 🎛️ Filter / Slicer  

## 🎯 Objective  
👉 Allow **interactive filtering**  

## 🧭 Fields  
- Use any categorical column  
  (Category, Region, Segment)  

## 📌 Examples  

### ✅ Example 1  
- Slicer → Region  

👉 Filters all visuals by region  

### ✅ Example 2  
- Slicer → Category  

👉 Filters dashboard by category  

---

# 1️⃣1️⃣ 📊 Clustered Column Chart  

## 🎯 Objective  
👉 Compare **categories side-by-side**  

## 🧭 Axis Selection  
- X-axis → Category  
- Y-axis → Sales / Profit  

## 📌 Examples  

### ✅ Example 1  
- Category vs Sales  

👉 Compare sales across categories  

### ✅ Example 2  
- Region vs Profit  

👉 Compare profit across regions  

---

# 🎯 How to Choose Chart  

| ❓ Question Type | 📊 Chart |
|----------------|--------|
| Compare categories | Stacked / Clustered Column |
| Show percentage | Pie / Donut |
| Show trend | Line Chart |
| Show ranking | Funnel |
| Show single value | KPI |
| Show ranking over time | Ribbon |
| Show hierarchy | Tree Map |
| Show location | Map |
| Apply filtering | Slicer |

---

# 🧠 Teaching Steps  

👉 Step 1: Identify question  
👉 Step 2: Find categorical column  
👉 Step 3: Find numerical column  
👉 Step 4: Choose correct chart  

---

✨ This guide helps students **understand + apply + choose charts based on questions**
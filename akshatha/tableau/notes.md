# 📊 Tableau Superstore Dashboard – Complete Step-by-Step Guide

---

# 🎯 Dashboard Objective
Create a **Sales & Profit Analysis Dashboard** using Superstore dataset.

---

# 🧾 Step 1: Connect Data

1. Open Tableau
2. Click **Connect → Microsoft Excel**
3. Load **Superstore Dataset**

---

# 🧹 Step 2: Data Preparation

Ensure correct data types:

| Field | Type |
|------|------|
| Sales | Measure |
| Profit | Measure |
| Quantity | Measure |
| Order Date | Date |
| Region | Dimension |
| Category | Dimension |
| Sub-Category | Dimension |
| State | Dimension |

---

# 📊 Step 3: Create Charts

---

## 1️⃣ Bar Chart – Sales by Region

**Fields:**
- Columns → Region
- Rows → Sales

**Enhancements:**
- Sales → Label
- Sort Descending

**Use Case:**
- Compare categories

---

## 2️⃣ Line Chart – Sales Trend

**Fields:**
- Columns → Order Date (Month/Year)
- Rows → Sales

**Marks:** Line

**Use Case:**
- Show trend over time

---

## 3️⃣ Pie Chart – Category Contribution

**Fields:**
- Marks → Pie
- Category → Color
- Sales → Angle
- Sales → Label

**Use Case:**
- Show part-to-whole relationship

---

## 4️⃣ Bar Chart – Profit by Sub-Category

**Fields:**
- Columns → Sub-Category
- Rows → Profit

**Enhancements:**
- Profit → Color (Green/Red)

**Use Case:**
- Identify profit/loss areas

---

## 5️⃣ Map – Sales by State

**Fields:**
- State → Detail
- Sales → Color
- Sales → Size

**Use Case:**
- Geographic analysis

---

## 6️⃣ KPI Cards

### Total Sales
- Sales → Text

### Total Profit
- Profit → Text

### Total Orders
- Order ID → Text → COUNT

**Use Case:**
- Summary metrics

---

## 7️⃣ Scatter Plot (Bubble Chart)

**Fields:**
- Columns → Sales
- Rows → Profit
- Category → Color
- Sales → Size

**Use Case:**
- Relationship between variables

---

## 8️⃣ Heat Map

**Fields:**
- Rows → Sub-Category
- Columns → Region
- Sales → Color

**Use Case:**
- Identify patterns and intensity

---

## 9️⃣ Histogram

**Fields:**
- Profit → Columns
- (Create Bin)
- Number of Records → Rows

**Use Case:**
- Distribution of data

---

## 🔟 Box Plot

**Fields:**
- Columns → Category
- Rows → Sales

**Marks:** Box Plot

**Use Case:**
- Show distribution, median, outliers

---

## 1️⃣1️⃣ Tree Map

**Fields:**
- Category → Color
- Sales → Size

**Use Case:**
- Hierarchical data comparison

---

## 1️⃣2️⃣ Area Chart

**Fields:**
- Columns → Order Date
- Rows → Sales

**Marks:** Area

**Use Case:**
- Show cumulative trends

---

## 1️⃣3️⃣ Dual Axis Chart

**Fields:**
- Columns → Order Date
- Rows → Sales + Profit

**Steps:**
- Right-click → Dual Axis

**Use Case:**
- Compare two measures

---

# 🧱 Step 4: Create Dashboard

1. Click **Dashboard → New Dashboard**
2. Set size → Automatic

---

# 🧩 Layout Design

### Top Section:
- KPI Cards (Sales | Profit | Orders)

### Middle Section:
- Sales by Region (Bar)
- Sales Trend (Line)

### Bottom Section:
- Pie Chart
- Profit Bar
- Map
- Heat Map / Scatter Plot

---

# 🎛️ Step 5: Add Filters

**Fields:**
- Region → Filters → Show Filter

**Apply to All Worksheets:**
- Right-click filter → Apply to Worksheets → All

---

# 🔄 Step 6: Add Interactivity

1. Dashboard → Actions
2. Add → Filter Action

**Example:**
- Click Region → Updates all charts

---

# 🎨 Step 7: Formatting

- Add Titles
- Use consistent colors
- Show labels where needed
- Remove unnecessary gridlines

---

# 🎯 Final Insights

Students should answer:
- Which region has highest sales?
- Which category performs best?
- Which sub-category has loss?
- What is the sales trend?
- Which state contributes more?

---

# 🧠 Teaching Flow

1. Create charts individually
2. Explain each chart
3. Build dashboard
4. Add filters
5. Add interactivity

---

# 🎤 Classroom Line

“Dashboard is a combination of multiple charts that provides complete business insights in one screen.”

---

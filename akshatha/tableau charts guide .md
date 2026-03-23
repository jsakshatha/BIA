# 📊 Tableau Complete Guide (Superstore Dataset)

---

## 🔹 STEP 1: Connect to Data

1. Open Tableau Desktop  
2. Click **Microsoft Excel**  
3. Select **Sample - Superstore.xls**

---

## 🔹 STEP 2: Data Source Understanding

### Tables Available:
- Orders (Main table)
- Returns
- People

### Key Points:
- Tableau auto-creates relationships  
- Orders table contains:
  - Customer info
  - Product info
  - Sales & Profit  

👉 Click **Sheet 1** to start

---

## 🔹 STEP 3: Tableau Interface

### Sections:
- **Columns Shelf** → X-axis  
- **Rows Shelf** → Y-axis  
- **Marks Card** → Color, Size, Label  
- **Filters Shelf** → Apply filters  
- **Show Me Panel** → Suggest charts  

### Trainer Note:
👉 Drag & Drop fields to create visuals

---

## 🔹 STEP 4: Bar Chart (Sales by Category)

### Steps:
- Drag **Category → Rows**
- Drag **Sales → Columns**

### Enhancement:
- Drag **Sales → Label**
- Click **Sort Descending**

---

## 🔹 STEP 5: Drill Down (Sub-Category)

### Steps:
- Drag **Sub-Category → Rows (below Category)**

👉 Creates hierarchical view

---

## 🔹 STEP 6: Profit Analysis

### Steps:
- Replace **Sales with Profit**
- Drag **Profit → Columns**

👉 Compare profitability

---

## 🔹 STEP 7: Line Chart (Sales Trend)

### Steps:
- Drag **Order Date → Columns**
- Convert to **Month (Continuous)**
- Drag **Sales → Rows**

---

## 🔹 STEP 8: Pie Chart (Sales by Region)

### Steps:
- Change Marks → **Pie**
- Drag **Region → Color**
- Drag **Sales → Angle**
- Drag **Sales → Label**

---

## 🔹 STEP 9: Map (Sales by State)

### Steps:
- Drag **State → View**
- Drag **Sales → Color**
- Drag **Sales → Size**

👉 Tableau auto-generates map

---

## 🔹 STEP 10: KPI (Total Sales)

### Steps:
- New Sheet
- Drag **Sales → Text**

### Format:
- Increase font size  
- Add currency symbol ₹  

---

## 🔹 STEP 11: Filters

### Steps:
- Drag **Region → Filters**
- Right-click → **Show Filter**

👉 Enables interactivity

---

## 🔹 STEP 12: Create Dashboard

### Steps:
1. Click **New Dashboard**
2. Drag sheets:
   - Bar Chart  
   - Line Chart  
   - Pie Chart  
   - Map  
   - KPI  

---

## 🔹 STEP 13: Interactivity

### Steps:
- Click any chart
- Enable **Use as Filter**

👉 Clicking one visual filters others

---

## 🔹 STEP 14: Navigation Buttons

### Steps:
- Go to Dashboard
- Drag **Button**
- Set action → Navigate to sheet

---

## 🔹 STEP 15: Formatting

### Best Practices:
- Remove grid lines  
- Add titles  
- Use consistent colors  
- Align visuals properly  

---

# 📊 FINAL DASHBOARD LAYOUT

- Top → KPI (Total Sales)  
- Left → Category Bar Chart  
- Right → Sales Trend  
- Bottom → Map + Pie  

---

# ❌ COMMON MISTAKES

- Confusing Dimension vs Measure  
- Not changing date format  
- Overloading dashboard  
- Poor formatting  

---

# 🎓 TRAINER SCRIPT

👉 “Connect data → Build visuals → Create dashboard → Add interactivity”

---

# 🚀 ADVANCED TOPICS

## 🔹 Calculated Field (Profit Ratio)

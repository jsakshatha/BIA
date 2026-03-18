# 📊 Power BI DAX Measures 
---

# 🟢 PART 1: Navigation Steps (Very Important)

## 🔹 Step 1: Load Data
1. Open Power BI Desktop  
2. Click **Home → Get Data → Excel**  
3. Select dataset  
4. Click **Load**  

---

## 🔹 Step 2: Go to Report View
1. Click **Report Icon (left panel)**  
2. This is where visuals (charts) are created  

---

## 🔹 Step 3: Create Measure
1. Select your table  
2. Click **Modeling → New Measure**  
3. Type DAX formula  
4. Press **Enter**  

---

## 🔹 Step 4: Use Measure in Visual
1. Insert a chart (Bar / Table / Card)  
2. Drag measure into **Values section**  
3. Observe aggregated result  

---

# 🟢 PART 2: Basic Measures (Aggregation)

---

## ✅ Question 1: Calculate Total Sales

### DAX
    Total Sales = SUM([Sales])

### Explanation
Adds all values in Sales column  

---

## ✅ Question 2: Calculate Total Profit

### DAX
    Total Profit = SUM([Profit])

### Explanation
Adds all profit values  

---

## ✅ Question 3: Count Total Orders

### DAX
    Total Orders = COUNT([Order ID])

### Explanation
Counts number of orders  

---

## ✅ Question 4: Average Sales

### DAX
    Average Sales = AVERAGE([Sales])

### Explanation
Calculates average of sales  

---

# 🟢 PART 3: Conditional Measures

---

## ✅ Question 5: Total Profit only for Positive Profit

### DAX
    Positive Profit =
    CALCULATE(
        SUM([Profit]),
        [Profit] > 0
    )

### Explanation
Calculates sum only when profit is positive  

---

## ✅ Question 6: Total Sales for High Sales (>500)

### DAX
    High Sales Total =
    CALCULATE(
        SUM([Sales]),
        [Sales] > 500
    )

### Explanation
Filters and sums only high sales  

---

# 🟢 PART 4: Intermediate Measures

---

## ✅ Question 7: Profit Ratio

### DAX
    Profit Ratio = DIVIDE(SUM([Profit]), SUM([Sales]))

### Explanation
Shows profit as percentage of sales  

---

## ✅ Question 8: Total Discount Amount

### DAX
    Total Discount =
    SUMX(
        ,
        [Sales] * [Discount]
    )

### Explanation
Row-wise calculation (Sales × Discount) then summed  

---

## ✅ Question 9: Sales Last Year (Basic Concept)

### DAX
    Sales Last Year =
    CALCULATE(
        SUM([Sales]),
        SAMEPERIODLASTYEAR([Order Date])
    )

### Explanation
Compares current sales with previous year  

---

# 🟢 PART 5: Important Notes for Students

- Measures are **aggregations (not row-level)**  
- Used in **charts and dashboards**  
- Always use aggregation functions like SUM, COUNT  
- CALCULATE is very important for filtering  
- Use DIVIDE instead of / for safety  

---

# 🟢 PART 6: Difference (Column vs Measure)

| Feature | Column | Measure |
|--------|--------|--------|
| Level | Row-level | Aggregated |
| Stored | Yes | No |
| Use | Data preparation | Visualization |
| Example | Profit Category | Total Sales |

---

# 🟢 Learning Flow (Recommended)

1. SUM  
2. COUNT  
3. AVERAGE  
4. CALCULATE  
5. DIVIDE  
6. Time-based functions  

---

# 📊 Power BI DAX - Beginner Practice (Superstore Dataset)

---

# 🟢 PART 1: Navigation Steps (Very Important)

## 🔹 Step 1: Load Data
1. Open Power BI Desktop  
2. Click **Home → Get Data → Excel**  
3. Select dataset  
4. Click **Load**  

---

## 🔹 Step 2: Go to Data View
1. Click **Table Icon (left panel)**  
2. You will see rows and columns  

---

## 🔹 Step 3: Create New Column
1. Select your table  
2. Click **Modeling → New Column**  
3. Type DAX formula  
4. Press **Enter**  

---

## 🔹 Step 4: Verify Output
1. Scroll right  
2. Check new column values  
3. Validate row-by-row  

---

# 🟢 PART 2: Basic Level (Arithmetic Operations)

---

## ✅ Question 1: Add two columns (Sales + Profit)

### DAX
    Total Value = [Sales] + [Profit]

### Explanation
Adds Sales and Profit for each row  

---

## ✅ Question 2: Subtract Discount from Sales

### DAX
    Remaining Amount = [Sales] - [Discount]

### Explanation
Finds remaining amount after discount  

---

## ✅ Question 3: Multiply Sales and Quantity

### DAX
    Sales per Quantity = [Sales] * [Quantity]

### Explanation
Calculates total based on quantity  

---

# 🟢 PART 3: Basic Logical Conditions (IF)

---

## ✅ Question 4: Profit or Loss

### DAX
    Profit Status = IF([Profit] > 0, "Profit", "Loss")

### Explanation
Checks whether profit is positive or negative  

---

## ✅ Question 5: High or Low Sales

### DAX
    Sales Level = IF([Sales] > 500, "High", "Low")

### Explanation
Classifies sales into two categories  

---

# 🟢 PART 4: Intermediate Level (Real-Time Usage)

---

## ✅ Question 6: Net Sales after Discount

### DAX
    Net Sales = [Sales] * (1 - [Discount])

### Explanation
Calculates actual sales after applying discount  

---

## ✅ Question 7: Profit Category

### DAX
    Profit Category =
    IF(
        [Profit] < 0, "Loss",
        IF([Profit] <= 100, "Low Profit", "High Profit")
    )

### Explanation
Classifies profit into categories  

---

## ✅ Question 8: Extract Year from Order Date

### DAX
    Order Year = YEAR([Order Date])

### Explanation
Extracts year for trend analysis  

---

## ✅ Question 9: Delivery Days

### DAX
    Delivery Days = DATEDIFF([Order Date], [Ship Date], DAY)

### Explanation
Calculates shipping delay  

---

## ✅ Question 10: Region Zone Classification

### DAX
    Region Zone =
    SWITCH(
        [Region],
        "East", "Zone 1",
        "West", "Zone 2",
        "Central", "Zone 3",
        "South", "Zone 4",
        "Other"
    )

### Explanation
Groups regions into zones  

---

## ✅ Question 11: Sales Category

### DAX
    Sales Category =
    IF(
        [Sales] < 100, "Low",
        IF([Sales] <= 500, "Medium", "High")
    )

### Explanation
Categorizes sales into levels  

---

# 🟢 PART 5: Important Notes for Students

- No need to use table name inside same table  
- Always check column names  
- Use IF for simple logic  
- Use SWITCH for multiple conditions  
- Practice step by step  

---

# 🟢 Learning Flow (Recommended)

1. Addition  
2. Subtraction  
3. Multiplication  
4. IF Condition  
5. Real-time examples  

---

# 🎯 End Goal

Students should be able to:
- Create new columns  
- Apply basic logic  
- Understand row-level calculations  

---

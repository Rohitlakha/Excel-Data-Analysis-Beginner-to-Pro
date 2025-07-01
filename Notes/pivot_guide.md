## 📘 Pivot Table Guide

### 🧩 How to Create a Pivot Table in Excel

1. **Select Your Data Range**
   - Example: `A1:D100` (make sure your data has headers)

2. **Insert Pivot Table**
   - Go to: `Insert` → `PivotTable`
   - Choose to place it in a **New Worksheet** or **Existing Worksheet**

3. **Pivot Table Fields Explained**
   | Section   | Purpose                                          | Example                            |
   |-----------|--------------------------------------------------|------------------------------------|
   | **Rows**     | Categories to group by                           | Product, Region                    |
   | **Columns**  | Optional sub-categories                          | Year, Gender                       |
   | **Values**   | Aggregated numerical data                        | Total Sales, Count, Average        |
   | **Filters**  | Top-level filters for the entire pivot           | Filter by Region or Department     |

---

### 🔄 Common Pivot Table Use Cases

- **Summarize Sales by Region**
  - Drag `Region` to **Rows**
  - Drag `Sales` to **Values** → Set to **Sum**

- **Count Employees by Department**
  - `Department` → Rows  
  - `Employee ID` or `Name` → Values → Set to **Count**

- **Sales by Product by Year**
  - `Product` → Rows  
  - `Year` → Columns  
  - `Sales` → Values → Sum

---

### 🎨 Formatting Tips

- **Value Field Settings**  
  Right-click a value → `Value Field Settings`  
  Choose **Sum**, **Average**, **Count**, etc.

- **Number Formatting**  
  In the same menu, click **Number Format** to set Currency, Percentage, etc.

- **Add Multiple Value Metrics**  
  Add the same field multiple times with different summaries (e.g., Sum and Count of Sales)

- **Use Slicers for Filters**
  - Go to: `PivotTable Analyze` → `Insert Slicer`
  - Select a field like `Region` or `Category` for quick filtering

---

### ⚙️ Best Practices

- Use **Excel Tables** (Ctrl + T) before inserting PivotTables to auto-update with new data.
- Always **clean your data** (no merged cells, empty headers, or mixed data types).
- Rename your pivot fields for clarity in reports and dashboards.

---

### 📌 Example Screenshot (if included in repo)

![Pivot Table Example](https://github.com/Rohitlakha/Excel-Data-Analysis-Beginner-to-Pro/blob/3fa207323437c0c5e235e9acfcf5170e6d05868e/Screenshots/Pivot%20Table%20Example.png)

---

This guide helps you build powerful summaries and dashboards in Excel using Pivot Tables. Ideal for business analysis, reporting, and performance tracking.

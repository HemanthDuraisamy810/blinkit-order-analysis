# 📊 BlinkIT Grocery Sales Dashboard  

## 🏆 Project Overview  
This project analyzes grocery sales data from BlinkIT to identify trends, customer preferences, and operational efficiencies. The dashboard was created using **Power BI**, leveraging data visualization techniques to uncover meaningful insights for better decision-making.  

## ❓ Problem Statement  
The goal of this project is to help BlinkIT optimize its operations by:  
- Understanding sales trends across different product categories.  
- Identifying the impact of store location and type on sales.  
- Analyzing customer preferences based on product ratings and visibility.  
- Determining key factors that influence sales performance.  

## 📂 Dataset Details  
The dataset consists of multiple attributes related to BlinkIT grocery sales, including:  
- **Item Identifier** – Unique code for each product.  
- **Item Fat Content** – Nutritional category (e.g., Low Fat, Regular).  
- **Item Type** – Category of the product (e.g., Fruits & Vegetables, Meat, Soft Drinks).  
- **Item Visibility** – The percentage of shelf space occupied by the product.  
- **Item Weight** – Weight of the item in grams.  
- **Outlet Identifier** – Unique code for each store.  
- **Outlet Establishment Year** – Year when the store was established.  
- **Outlet Location Type** – Classification of stores based on tier (Tier 1, Tier 2, Tier 3).  
- **Outlet Size** – Size of the store (Small, Medium, Large).  
- **Outlet Type** – Type of outlet (Supermarket Type1, Type2, Type3, Grocery Store).  
- **Sales** – Total sales revenue generated for each product.  
- **Rating** – Customer ratings of the products.  

## ⚙️ Steps Followed  


- **Step 1:** Loaded Blinkit sales and delivery dataset into Power BI (CSV format).
- **Step 2:** Opened Power Query Editor and checked **column distribution, column quality, and column profile** options.
- **Step 3:** Ensured column profiling was based on the entire dataset to get accurate insights.
- **Step 4:** Identified missing values and handled them appropriately in delivery time and order status columns.
- **Step 5:** Created **calculated columns** and **measures** using DAX for key metrics such as:
  - Total Orders
  - Total Revenue
  - Average Delivery Time
  - Order Completion Rate
- **Step 6:** Used visual filters (slicers) for:
  - City/Location
  - Time of Order (Morning, Afternoon, Evening, Night)
  - Category of Items Ordered
- **Step 7:** Added key **visualizations**:
  - **Card visuals** for total orders, revenue, and delivery time.
  - **Bar charts** for category-wise sales and delivery performance.
  - **Line charts** to track order trends over time.
  - **Heatmaps** to analyze delivery efficiency across different locations.
- **Step 8:** Created a new **calculated column** to segment customers into different spending groups based on order value.
- **Step 9:** Used a **gauge chart** to track real-time delivery performance against company benchmarks.
- **Step 10:** Published the report to **Power BI Service** for sharing and collaboration.

---

## 🔍 Key Insights  

### 1️⃣ Total Orders and Revenue  
- **Total Orders:** 8,523  
- **Total Revenue:** ₹1,201,681.49    

### 2️⃣ Order Completion Rate  
- ✅ **Completed Orders:** 100%  
- ❌ **Cancelled Orders:** 0%  
  
### 3️⃣ Best-Performing Product Categories  
- 🥦 **Fruits & Vegetables**  
- 🍿 **Snack Foods**  
- 🏠 **Household Items**  

### 4️⃣Outlet Establishment Year vs. Sales  
- Older stores (**established before 2015**) performed **better in sales**.  
- Newer stores (**established after 2020**) struggled with lower average revenue.

### 5️⃣ Customer Preferences  
- Customers preferred **"Regular Fat" products over "Low Fat"**.  
- **Frozen Foods and Canned Items** saw higher demand compared to Soft Drinks.  
- Stores in **Tier 2 cities** had **more demand for health-related products**.  



---

## 📢 Future Recommendations  
✅ Increase marketing efforts for **low-rated but high-visibility products** to improve sales.  
✅ Invest in **expanding high-performing stores (Supermarket Type1) in Tier 3 locations**.  
✅ Optimize inventory by **stocking more Fruits & Vegetables and Snack Foods**, as they drive higher sales.  
✅ Improve the shelf placement of **Health & Hygiene products** to increase visibility.  
✅ Offer promotions or bundle deals for **lower-performing product categories**.  

## 🛠️ Technologies Used  
- **Power BI** – Data visualization and dashboard creation  
- **DAX (Data Analysis Expressions)** – Used for calculated columns and measures  
- **Excel** – Data cleaning and preprocessing 
## Report Snapshots

**Power BI Service Dashboard:**  
![Image](https://github.com/user-attachments/assets/b0429d89-381f-40dc-bc08-54ae3371cf7c)


## 📊 Dashboard Link  
🔗 **[View BlinkIT Grocery Dashboard](https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection)**  

---

## 👨‍💻 **About the Developer**  
🔹 **Hemanth Duraisamy** | Data Analyst 📊  
📧 Email: hemanthduraisamy@gmail.com  
💼 LinkedIn: [Your Profile Here]((https://www.linkedin.com/in/hemanth-d-551016249/))  

🌟 **Feedback & contributions are always welcome!** 🚀💡  

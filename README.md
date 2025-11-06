# ⚡ EV Sales Analysis in India (2014–2024)

### 🚗 Overview
This project analyzes the **growth and trends of Electric Vehicles (EVs)** in the Indian automobile market using real-world data.  
It compares **EV and ICE (Internal Combustion Engine)** car models, explores **sales performance**, and highlights **emerging market insights** using **Python** and **Power BI**.

---

### 📊 Objectives
- Compare **EV vs ICE** models in terms of price, range, and availability.  
- Explore **EV sales trends** across states and vehicle classes from 2014 to 2024.  
- Identify **top-performing states**, **growth periods**, and **market share** of each vehicle type.  
- Visualize insights with an interactive **Power BI dashboard**.

---

### 🧾 Datasets Used
1. **Car Models Dataset** – Contains Indian car models (EV + ICE) with specifications:
   - Price, Mileage/Range, Type (EV or ICE), Year, Brand, etc.  
2. **EV Sales Dataset** – Records EV sales by:
   - Year, Vehicle Class (2W, 3W, 4W, Bus), State, and Quantity  

Source: Public automotive datasets and aggregated EV sales reports (cleaned & transformed).

---

### 🧹 Data Cleaning & Preparation (Python)
Performed using **Pandas** and **NumPy**:
- Removed missing and inconsistent values  
- Renamed columns for clarity (e.g., `Ex_Showroom_Price_(₹_Lakhs)` → `Price`)  
- Converted text-based prices into numeric ranges  
- Standardized categorical labels (EV/ICE)  
- Merged datasets for Power BI analysis  
- Exported cleaned data:

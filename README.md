# 🚗 OIBSIP ML Internship – Task 3  
## Car Price Prediction using Machine Learning  

### 🔹 Objective  
Build a **Machine Learning model** to predict the **resale price of used cars** based on multiple features like year, present price, kilometers driven, fuel type, seller type, transmission, and number of owners.  

---

### 🔹 Dataset  
The dataset contains the following columns:  
- **Car_Name** – Model of the car  
- **Year** – Manufacturing year  
- **Present_Price** – Current ex-showroom price (in lakhs)  
- **Kms_Driven** – Distance driven (in kilometers)  
- **Fuel_Type** – Petrol / Diesel / CNG  
- **Seller_Type** – Dealer / Individual  
- **Transmission** – Manual / Automatic  
- **Owner** – Number of previous owners  
- **Selling_Price** – Target variable (resale price of the car)  

---

### 🔹 Steps Performed  
1. Imported dataset and performed exploratory data analysis (EDA)  
2. Encoded categorical variables into numerical form  
3. Visualized relationships using **correlation heatmap**  
4. Split dataset into **training (80%)** and **testing (20%)** sets  
5. Trained two ML models:  
   - **Linear Regression**  
   - **Random Forest Regressor**  
6. Evaluated models using **R² Score**  
7. Identified **feature importance** using Random Forest  
8. Predicted car prices on test samples  

---

### 🔹 Tools & Libraries  
- **Python**  
- **Pandas, NumPy** – Data Handling  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-Learn** – Model Training & Evaluation  
- **Jupyter Notebook / Python Script** – Implementation  

---

### 🔹 Results / Outcome  
✔️ **Random Forest outperformed Linear Regression** in prediction accuracy  
✔️ Found that **Year, Present Price, and Kms Driven** are the most important features  
✔️ Visualized feature importance and correlations  
✔️ Successfully predicted resale prices for sample test cases  

---

### 🔹 Author  
👩‍💻 **Varsha** – OIBSIP ML Intern  

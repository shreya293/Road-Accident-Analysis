# 🚗 Regulatory Affairs of Road Accident Data 2020 India

## 📌 Project Overview
This project analyzes **road accident data for million-plus cities in India (2020)** to uncover accident trends, causes, and their outcomes.  
Using **Python, Pandas, Matplotlib, and Seaborn**, the data is cleaned, analyzed, and visualized to identify patterns that can help improve road safety policies.

Dataset Source: [data.gov.in - Road Accidents in India 2020](https://data.gov.in/catalog/road-accidents-india-2020)  
Dataset Link: [Download Here](https://drive.google.com/file/d/1ft84zICATQqhB1egy4DQJs4bIckcA-0f/view?usp=sharing)  

---

## 🛠 Tools & Technologies
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Tools**: Jupyter Notebook, Excel  
- **Domain**: Data Analysis

---

## 📊 Dataset Information
The dataset contains:
1. **Million Plus Cities** – Name of the city  
2. **Cause Category** – Broad classification of accident causes  
3. **Cause Subcategory** – Detailed cause description  
4. **Outcome of Incident** – Injuries, deaths, or total accidents  
5. **Count** – Number of incidents  

---

## 📈 Steps Followed
1. **Data Loading & Inspection** – Load CSV, inspect structure, and check missing values  
2. **Data Cleaning** – Remove or handle null values, standardize formats  
3. **Exploratory Data Analysis (EDA)** –  
   - Accident distribution by city  
   - Accident cause patterns  
   - Outcome-based analysis  
4. **Cause vs Outcome Analysis** – Compare accident causes to fatalities/injuries  
5. **Visualization** – Use bar charts and stacked plots for insights  

---

## 📌 Key Insights
- Identified top cities with the highest accident counts  
- Found most common accident causes and subcategories  
- Studied links between causes and outcomes to reveal high-risk scenarios  

---

## 📍 Conclusion
The analysis provides results **based on historical accident data** by grouping and visualizing:
- City-wise accident counts  
- Frequency of cause categories and subcategories  
- Incident outcomes (injuries, fatalities, total accidents)  

From these patterns, we can identify **which causes are more dangerous** and **which cities need urgent safety measures**.  
These insights can guide **traffic authorities** to take targeted, data-driven actions.

---

## 📂 Project Structure

📦 Road_Accident_Analysis_India
┣ 📜 analysis.ipynb # Jupyter Notebook with analysis code
┣ 📜 road_accident_data.csv # Dataset
┣ 📜 README.md # Project Documentation
┗ 📜 requirements.txt # Python dependencies


---

## 🚀 How to Run the Project
1. **Clone this repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Road_Accident_Analysis_India.git

2. **Navigate to the Folder:**
   ```bash
   cd Road_Accident_Analysis_India

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook analysis.ipynb


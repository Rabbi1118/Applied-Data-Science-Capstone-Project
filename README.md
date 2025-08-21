# SpaceX Falcon 9 First Stage Landing Prediction

## 📌 Project Overview
This project explores predictive factors influencing the successful landing of **SpaceX Falcon 9 rocket’s first stage**.  
By combining data from the **SpaceX API** and **Wikipedia web scraping**, the project applies **data wrangling, exploratory analysis, interactive dashboards, and machine learning models** to predict landing success.  

The **Decision Tree classifier** achieved the best performance with an accuracy of **88.9%**.  
Insights from this analysis can support **mission planning, risk assessment, and aerospace decision-making**.  

---

## 🚀 Features
- **Data Collection**
  - Retrieved launch data via **SpaceX REST API**
  - Performed **web scraping** from Wikipedia launch records
- **Data Wrangling**
  - Cleaned missing values, standardized features, encoded categorical data
- **Exploratory Data Analysis (EDA)**
  - Visualizations of success rate by payload, orbit, and launch site
  - SQL queries for deeper insights into booster versions, payloads, and mission outcomes
- **Interactive Analytics**
  - **Folium maps** to visualize launch sites and outcomes
  - **Plotly Dash dashboards** with interactive charts (site-wise success rates, payload success trends)
- **Predictive Analysis**
  - Implemented Logistic Regression, KNN, Decision Tree, and SVM
  - Tuned models with **GridSearchCV**
  - Evaluated performance with **accuracy score and confusion matrix**
  - Best Model: **Decision Tree (88.9% accuracy)**

---

## 📊 Results
- **Decision Tree** – 88.9%  
- Logistic Regression – 83.3%  
- Support Vector Machine (SVM) – 83.3%  
- K-Nearest Neighbors (KNN) – 83.3%  

Key Findings:
- **Launch success improved significantly after 2017**, reflecting SpaceX’s technological maturity  
- **KSC LC-39A** had the highest launch success rate (76.9%)  
- **Orbit type and payload mass strongly influenced landing outcomes**  
- Geospatial mapping highlighted launch sites clustered near coasts  

---

## 🛠️ Tools & Libraries
- **Python**  
- **Pandas, NumPy** – data wrangling  
- **Matplotlib, Seaborn, Plotly** – visualization  
- **Folium** – geospatial analysis  
- **BeautifulSoup, Requests** – web scraping  
- **Scikit-learn** – machine learning models & evaluation  
- **SQL** – structured querying for insights  

---

## 📚 Learning Outcomes
- Hands-on experience with **API data extraction** and **web scraping**  
- Applied **EDA and SQL** for extracting insights from aerospace data  
- Built **interactive dashboards** for exploratory analytics  
- Compared **multiple ML models** for predictive performance  
- Identified **key success factors** in Falcon 9 landings  

---

🔍 This project demonstrates how **data science and machine learning** can drive insights in the **aerospace industry**, supporting **operational decision-making and risk management**.  

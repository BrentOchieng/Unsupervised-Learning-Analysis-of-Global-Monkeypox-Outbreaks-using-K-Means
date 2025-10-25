# Global Monkeypox Outbreak Clustering and Visualization using K-Means 

## Overview

This project explores **global Monkeypox outbreak patterns** using the **K-Means clustering algorithm** to identify groups of countries with similar epidemiological profiles.  
The analysis draws from publicly available data on **confirmed cases**, **deaths**, and **previous exposure history**, aiming to uncover regional similarities and global clustering trends.  

Through the use of **unsupervised machine learning** and **interactive visualizations** (via Plotly and Seaborn), this project highlights how clustering can help inform public health monitoring, outbreak preparedness, and data-driven decision-making.
--

>  **View the full interactive notebook here:**  
> [ Open in NBViewer](https://nbviewer.org/github/BrentOchieng/Unsupervised-Learning-Analysis-of-Global-Monkeypox-Outbreaks-using-K-Means/blob/main/Clustering_Monkeypox_Outbreak_Patterns_Across_the_Countries_Using_K_Means_Algorithm.ipynb)


---

##  Objectives

- Identify clusters of countries with similar Monkeypox outbreak characteristics.  
- Explore correlations between **cases**, **deaths**, and **historical exposure**.  
- Visualize how outbreak severity varies across regions globally.  
- Provide insights to support **global health surveillance and response planning**.

---

##  Methodology

1. **Data Collection**  
   - The dataset includes global records of Monkeypox outbreaks with fields such as:
     - `Country`
     - `Cases`
     - `Deaths`
     - `Previous_Cases` (1/0 – indicating prior Monkeypox experience)

2. **Data Preprocessing**
   - Missing values handled and categorical variables encoded.  
   - Numeric features normalized to prepare for clustering.  

3. **K-Means Clustering**
   - The K-Means algorithm was applied to group countries based on outbreak metrics.  
   

4. **Visualization**
   - **Choropleth maps (Plotly)** were used to show the global distribution of clusters.  
   - **Bar charts (Seaborn)** highlighted top countries by deaths and case counts.  

---

##  Key Findings

- Countries with **previous exposure to Monkeypox** tended to have **lower fatality rates**, suggesting possible immunity or stronger response systems.  
- **High-burden countries** formed a distinct cluster, marked by higher death counts and active outbreaks.  
- A separate cluster included **countries with minimal or no cases**, highlighting areas with low exposure or effective containment.  
- Regional patterns emerged, showing that **geographic proximity** often aligned with cluster grouping — reflecting shared exposure and response conditions.  

---

##  Technologies Used

| Category | Tools & Libraries |
|-----------|------------------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Machine Learning | Scikit-learn (KMeans) |
| Visualization | Plotly, Seaborn, Matplotlib |
| Environment | Google Colab / Jupyter Notebook |

---

##  Project Structure

Global_Monkeypox_Clustering/

│

├── data/

│ └── monkeypox_global_data.csv

│

├── notebooks/

│ └── Clustering_Monkeypox_Outbreak_Patterns.ipynb

│

├── visualizations/

│ ├── monkeypox_clusters_map.html

│ └── top10_deaths_barplot.png

│

├── README.md

└── requirements.txt


---

##  Results and Insights

The results of this analysis demonstrate the potential of **unsupervised learning** in understanding global health data without pre-labeled outcomes.  
By clustering similar countries based on outbreak metrics, the model reveals underlying structures that can:
- Inform **public health strategies**
- Support **resource allocation**
- Guide **targeted interventions** in high-risk regions  

---

##  Conclusion

This project illustrates how **data clustering and visualization** can be applied to epidemiological data to extract actionable insights.  
By combining **machine learning** and **exploratory data analysis**, it enhances our understanding of **global Monkeypox spread patterns**, helping inform both policy and research efforts.

---

##  Data Source

> U.S. Centers for Disease Control and Prevention (CDC)  
> *(Monkeypox Global Surveillance Data, 2025. link-https://www.cdc.gov/monkeypox/data-research/cases/world-map.html#data-table-/wcms/vizdata/Mpox/MPX-Cases-Deaths-by-Country-Clade.csv)*

---

##  Analysis and Visualization by

> **Brent Ochieng (2025)**  
> *Data Science & Analytics Enthusiast*




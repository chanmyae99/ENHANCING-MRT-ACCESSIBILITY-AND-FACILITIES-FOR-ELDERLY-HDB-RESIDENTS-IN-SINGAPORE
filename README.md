# ENHANCING-MRT-ACCESSIBILITY-AND-FACILITIES-FOR-ELDERLY-HDB-RESIDENTS-IN-SINGAPORE

This project was developed for the **EGT204 Data Preparation & Visualization (DPV)** module.  
It analyses **MRT station accessibility in Singapore** using public datasets to identify accessibility gaps affecting elderly and mobility-challenged users.

The project follows the **CRISP-DM framework**, with strong emphasis on **data preparation, integration, and visualization**.

---

## 📌 Project Overview

Singapore’s ageing population increases the importance of **inclusive and accessible public transport**.  
While MRT stations are widely available, accessibility facilities and coverage vary across stations and regions.

This project uses data analytics and visualization to:
- Analyse MRT accessibility facilities
- Compare stations across regions and lines
- Identify stations that may require priority improvements

---

## 🧠 CRISP-DM Methodology

### 1️⃣ Business Understanding

**Problem Statement**  
Not all MRT stations provide equal accessibility support, especially in areas with high elderly population density.

**Objectives**
- Analyse MRT station accessibility using multiple datasets  
- Identify stations with lower accessibility support  
- Support data-driven decision making for inclusive transport planning  

**Success Criteria**
- Clean and integrated datasets  
- Clear visual insights on accessibility gaps  
- Actionable findings for improvement prioritisation  

---

### 2️⃣ Data Understanding

**Datasets Used**
- MRT station information (station name, line, location)
- Accessibility facilities data
- Elderly population data by planning area

**Initial Data Exploration**
- Reviewed dataset size, structure, and attributes  
- Identified relevant accessibility-related columns  
- Checked for missing values and inconsistencies  
- Understood how datasets could be linked  

---

### 3️⃣ Data Preparation *(Core DPV Focus)*

This phase focused on transforming raw data into analysis-ready datasets.

**Data Cleaning**
- Removed duplicate and irrelevant records  
- Handled missing values  
- Standardised column names and formats  

**Data Integration**
- Merged MRT station data with accessibility facilities data  
- Linked elderly population data to MRT coverage areas  
- Validated merged datasets for accuracy  

**Feature Engineering**
- Created accessibility indicators  
- Derived simple accessibility scores for comparison  

At the end of this phase, the data was **clean, consistent, and ready for visualization**.

---

### 4️⃣ Modelling (Exploratory Analysis)

Although this is a DPV project, a simple **distance-based analytical approach** was applied to support accessibility analysis.

A **Nearest Neighbour model** from **scikit-learn (`NearestNeighbors`)** was used to:

- Measure the proximity between MRT stations and nearby residential or accessibility-related locations
- Quantify accessibility based on shortest distance
- Support objective comparison between stations

This approach does **not perform prediction**.  
It is used purely as an **analytical technique** to calculate spatial proximity and accessibility indicators.

As this is a **DPV project**, modelling focuses on **descriptive and exploratory analysis**, not machine learning.

**Analysis Performed**
- Compared accessibility levels across MRT stations  
- Analysed MRT coverage in elderly-dense areas  
- Compared accessibility across MRT lines and regions  

Simple aggregations and comparisons were used to support visual insights.

---

### 5️⃣ Evaluation

**Evaluation Criteria**
- Alignment with project objectives  
- Clarity of insights produced  
- Effectiveness of visualizations  

**Key Findings**
- Accessibility varies significantly across MRT stations  
- Some elderly-dense areas are served by stations with limited accessibility  
- Interchange stations generally provide better accessibility coverage  

The results successfully meet the project objectives.

---

### 6️⃣ Deployment (Visualization & Communication)

A **Power BI dashboard** was developed to present findings clearly.

**Dashboard Features**
- Accessibility score comparison by station  
- Elderly population distribution  
- Filters by MRT line and region  
- Identification of low-accessibility stations  

The dashboard enables users to explore insights interactively and supports informed decision making.

---

## 🛠 Tools & Technologies

- **Python** (Pandas, NumPy)
- **Power BI** (DAX, interactive dashboards)
- Public open datasets (Singapore)

---

## 🧩 Skills Demonstrated

This project demonstrates my ability to:
- Apply the CRISP-DM framework
- Perform data cleaning and integration
- Prepare datasets for visualization
- Design meaningful KPIs and indicators
- Build interactive dashboards
- Translate data insights into real-world recommendations


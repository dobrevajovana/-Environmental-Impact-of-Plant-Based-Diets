# 🌱🌍 **Environmental Impact of Plant-Based Diets** 🍽️📉

### A Comprehensive Analysis Using Clustering & Data Visualization

[![DOI](https://img.shields.io/badge/DOI-10.1000/example-blue.svg)](https://doi.org/10.1000/example)  
[![GitHub](https://img.shields.io/github/license/jovanadobreva/Environmental-Impact-Plant-Based-Diets)](https://github.com/jovanadobreva/Environmental-Impact-Plant-Based-Diets/blob/main/LICENSE)

### Authors:  
👩‍💻 **Blagica Golubova**  
👩‍💻 **Fjola Fetaji**  
👩‍💻 **Jovana Dobreva**  
👩‍💻 **Milena Trajanoska**  
👩‍💻 **Ana Todorovska**  
👨‍💻 **Riste Stojanov**  
👨‍💻 **Dimitar Trajanov**

🎓 **Institution**:  
S. Cyril and Methodius University - Faculty of Computer Science & Engineering, Skopje, N. Macedonia

---

## 📜 **Introduction**
This repository contains the code and datasets used for the analysis presented in the paper **"Assessing the Environmental Impact of Plant-Based Diets"**. The study explores the significant differences in CO2 emissions between plant-based and animal-based diets through a combination of **data visualization** and **clustering techniques**. 🍃🌾

---

## 📈 **Key Features**
- **Data Analysis** 🗂️: Visualization of CO2eq emissions across 43 different food products.
- **Clustering** 🔍: Unsupervised clustering (using k-means) to categorize food products based on their environmental impact.
- **Mitigation Strategy** 🌍: Proposing strategies to reduce CO2 emissions by promoting plant-based diets.

---

## 🚀 **Getting Started**

### 1. **Clone the repository**  
```bash
git clone https://github.com/jovanadobreva/Environmental-Impact-Plant-Based-Diets.git
```
## 🛠️ Methodology

### 1. **Data Collection**  
- **Datasets**: The study utilizes two primary datasets:
  - **Kaggle dataset** containing 43 food products with details on CO2eq emissions, land use, and water consumption.
  - **FAO dataset** sourced from the Food and Agriculture Organization (FAO) on global food production for 34 food products.
  
- **Emissions Data**: The environmental impact of each food product was measured using CO2-equivalents (CO2eq), capturing not just carbon dioxide but also other greenhouse gases like methane and nitrous oxide.

### 2. **Data Analysis & Visualization**  
- We employed **bar charts**, **scatter plots**, and **pie diagrams** to analyze and visualize differences in CO2eq emissions across food products.
- Products were grouped into three categories: **plant-based**, **animal-based**, and **refined oils and sugars**.
  
### 3. **Clustering**  
- **K-means clustering** was applied to group the food products based on their CO2eq emissions.
- The **elbow method** was used to determine the optimal number of clusters, resulting in three main groups: **plant-based**, **animal-based**, and **refined foods**.

### 4. **Mitigation Strategy**  
- Based on the **EAT-Lancet Diet** guidelines, a scenario analysis was conducted to estimate the potential reduction in CO2 emissions if dietary shifts toward plant-based foods were adopted.
- Emissions were calculated using the recommended consumption percentages for various food groups, and the effects of decreasing meat production were explored.

---

## 📊 Results

### 1. **CO2eq Emissions**  
- The analysis showed a **significant difference** between the emissions of plant-based and animal-based products.
  - **Beef** 🐄 and other red meats had the highest CO2eq emissions, with **beef** producing approximately 60 kg CO2eq per kg of product.
  - **Plant-based foods** such as **nuts** 🌰 and **fruits** 🍎 showed the lowest emissions, often less than 1 kg CO2eq per kg.

### 2. **Clustering Results**  
- The clustering analysis grouped food products into three distinct clusters:
  - **Cluster 1**: Plant-based foods 🌱 (e.g., fruits, vegetables) with low CO2 emissions.
  - **Cluster 2**: Animal-based foods 🐄 (e.g., beef, lamb) with high emissions.
  - **Cluster 3**: Refined oils and sugars 🍬, where land-use impact was higher for the production of raw materials.

### 3. **Mitigation Strategy Results**  
- Reducing the production of animal-based foods, particularly **beef** and **sugar**, led to substantial reductions in emissions.
- Even a **minor reduction in meat production** resulted in a **significant reduction** in overall CO2 emissions.

### 4. **Impact of Dietary Changes**  
- A scenario where plant-based foods accounted for **73% of the diet**, animal foods for **25%**, and oils for **2%** showed a potential reduction of **26.7% in total CO2 emissions**.


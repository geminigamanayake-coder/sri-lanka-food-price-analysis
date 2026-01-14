# 🍚 Sri Lankan Food Prices Analysis

## Overview
This project analyzes **food price trends in Sri Lanka** using R programming and visualizes the findings through an interactive **R Shiny dashboard**. The analysis provides insights into commodity price patterns, regional differences, and price volatility across the country, supporting data-driven decision-making for policy planning and market monitoring.

---

## Dataset
The dataset contains historical food price data for multiple commodities across Sri Lanka.

- **Source:** World Food Programme (WFP) Price Database via HDX  
- **Format:** CSV  
- **Coverage:** Various markets and regions in Sri Lanka  
- **Key Variables:**  
  - `Country` – Always Sri Lanka  
  - `Market` – Location of the commodity  
  - `Category` – Food type (cereals, pulses, vegetables, oils, etc.)  
  - `Commodity` – Specific food item  
  - `Price` – Price in Sri Lankan Rupees (LKR)  
  - `Unit` – Measurement unit (kg, liter, etc.)  
  - `Date` – Date of record  

---

## Project Components

### 1. Data Preprocessing
- Cleaning missing or inconsistent values  
- Encoding categorical variables for modeling  
- Scaling numeric variables for clustering  

### 2. Data Mining & Modeling
- **Clustering:** K-Means and Hierarchical Clustering to group commodities by price behavior  
- **Association Rule Mining:** Apriori algorithm to detect co-occurring commodities and price trends  
- **Classification:** Logistic Regression used to predict price bands (low, medium, high)  

### 3. R Shiny Dashboard
- Interactive dashboard displaying:
  - Food prices over time  
  - Price comparisons across markets and regions  
  - Visualization in **LKR and USD**  
  - Filtering by commodity and location  

### 4. Report
- PDF report summarizing:
  - Data cleaning and preparation steps  
  - Methodology for clustering, association rules, and logistic regression  
  - Key findings and actionable insights  

---

## Key Findings
- **Staple commodities** like rice and wheat flour show a steady upward price trend  
- Urban markets, particularly Colombo, consistently have **higher prices** than rural markets  
- Currency depreciation against USD significantly impacts food affordability  
- Certain commodities demonstrate high price volatility due to import dependency and supply chain issues  
- Seasonal trends and festival periods influence commodity prices across regions  

---

## Limitations
- Dataset contains only 500 entries, limiting long-term temporal or seasonal analysis  
- Manual data updates restrict real-time monitoring  
- External shocks such as policy changes, climate events, or global market disruptions were not modeled  
- Dashboard design and R Shiny rendering limit complex visualizations  

---

## Recommendations
- Strengthen **domestic food production** to reduce reliance on imports  
- Expand **real-time food price monitoring** systems  
- Use dashboards to support **policy interventions** for price stability  
- Improve supply chains and market regulations to reduce volatility  
- Provide targeted **subsidies or support** for vulnerable populations  

---

## Challenges
- Cleaning and preprocessing inconsistent dataset values  
- Limited dataset size prevented extensive temporal analysis  
- Designing a **user-friendly dashboard** for both technical and non-technical users  
- Visualizing complex economic patterns clearly and accurately  

---

## Conclusion
The analysis demonstrates **significant regional disparities and price volatility** in Sri Lankan food markets. Rising prices, currency depreciation, and supply chain challenges threaten food affordability.  
The R Shiny dashboard provides an interactive platform for monitoring trends, supporting policy-making, and enabling early intervention to address **food insecurity and market instability**.  

---

## Author
**Gemini Gamanayake**  
BSc in Applied Data Science & Communication (UG)  
geminigamanayake@gmail.com  

---

## License
This project is for **educational purposes only**.  

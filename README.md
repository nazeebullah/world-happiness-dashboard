# world-happiness-dashboard
An interactive Tableau dashboard analyzing global happiness trends (2021-2024) for policy analysis, built for a UNDP user persona.
# 🌍 World Happiness Analysis Dashboard

## 📖 Project Overview
This project involved designing and building an interactive **Tableau dashboard** to analyze global happiness and well-being trends from 2021 to 2024. The dashboard was crafted specifically for a **UNDP Policy Analyst** persona, with the goal of identifying spatial and economic inequalities to inform data-driven policy decisions aligned with the UN's Sustainable Development Goals (SDGs).

**Primary Goal:** To transform the World Happiness Report dataset into an actionable tool for equitable policy-making.

## 📊 Dataset
**Source:** [World Happiness Report](https://worldhappiness.report/)
- **Time Frame:** 2021 - 2024
- **Key Metrics:** Ladder Score (Happiness), GDP per capita, Social Support, Healthy Life Expectancy, Freedom, Generosity, Perceptions of Corruption
- **Modifications:**
  - Added **Development Status** (Developed/Developing/Underdeveloped) based on World Bank income thresholds.
  - Added **Happiness Tier** classification (Very High, High, Medium, Low).
  - Geographically cleaned and imputed missing values for consistency.

## 🛠️ Tech Stack & Tools
- **Primary Tool:** Tableau Desktop
- **Data Preparation:** Excel, Tableau Prep
- **Methodologies:** Data Cleaning, Choropleth Mapping, Trend Analysis, Statistical Correlation
- **Design Principles:** Perceptual Effectiveness (Color Theory), Accessibility, Interaction Design

## 📁 Project Structure
world-happiness-dashboard/
├── data/ # Source and processed data (see note)
├── dashboard/ # Tableau packaged workbook (.twbx) and screenshots
├── reports/ # Final project report and documentation
└── README.md
## 🔧 Key Features of the Dashboard

### 1. Interactive Choropleth Map
- **Purpose:** Visualize geographical disparities in happiness (Ladder Score).
- **Interactivity:** Filter by Year, Region, and Development Status.
- **Encoding:** Red-Green diverging color palette (intuitive for "Low-High" happiness).

### 2. GDP vs. Happiness Scatter Plot
- **Purpose:** Analyze the correlation between economic strength and well-being.
- **Features:** Trend line with R² value (showing strong positive correlation ~0.93), colored by Development Status.

### 3. Diverging Bar Chart
- **Purpose:** Identify top 10 and bottom 10 countries by happiness score.
- **Insight:** Quick identification of overperformers (policy models) and underperformers (crisis zones).

### 4. Temporal Trend Analysis
- **Purpose:** Track the evolution of happiness scores by region from 2021-2024.
- **Finding:** Highlighted post-pandemic recovery in most regions and a concerning decline in Africa.

## 📈 Insights & Impact
- **Spatial Inequality:** Identified Sub-Saharan Africa and South Asia as priority regions for intervention.
- **Economic Correlation:** Confirmed a strong link between GDP per capita and happiness, especially in developing nations.
- **Temporal Trends:** Provided evidence for UNDP's strategic planning, showing which regions are recovering post-pandemic and which are falling behind.
- **Actionable Output:** The dashboard includes functionality to **export PDF reports** for stakeholder presentations, directly supporting the UNDP's "Leave No One Behind" mandate.

## 🎨 Design Rationale
- **User-Centered Design:** Built for a non-technical UNDP Policy Analyst persona, prioritizing clarity and ease of use.
- **Perceptual Effectiveness:** Utilized a red-green color scheme aligned with innate "danger-safe" associations, tested for colorblind accessibility.
- **Cross-Filtering:** Implemented interactive filters allowing users to trace insights across all visualizations simultaneously.

## 🔮 Future Enhancements
- **Real-Time Data Integration:** Connect the dashboard to the World Bank API for live GDP updates.
- **Advanced Forecasting:** Implement ARIMA models in Python/R to forecast happiness under different policy scenarios.
- **Multidimensional Metrics:** Add layers for Gender Inequality Index (GII) and Environmental Performance Index (EPI) for a more holistic view.

## 👨‍💻 Developer
**Nazeeb Ullah**
- MSc Data Science & Analytics | Economist
- [LinkedIn](https://www.linkedin.com/in/nazeeb-ullah-a812a3105)
- [GitHub](https://github.com/nazeebullah)

---
*This project was completed as part of the CSS803 Data Visualisation module at Brunel University London.*

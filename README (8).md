# 🚗⚡ Charging Ahead: Socioeconomic Inequities in Electric Vehicle Charging Infrastructure Across the United States

This repository contains the research, analysis, and findings from the study **"Charging Ahead: Socioeconomic Inequities in Electric Vehicle Charging Infrastructure Across the United States"** by Sagiv Antebi and Michael Fire. The project explores the relationship between socioeconomic factors and the distribution of Electric Vehicle (EV) charging infrastructure across the United States.

## 📂 Repository Contents

1. **📄 Paper**:  
   The research paper ([`Paper.pdf`](./Paper-Charging_Ahead_Socioeconomic_Inequities_in_Electric_Vehicle_Charging_Infrastructure_Across_the_United_States.pdf)) provides an in-depth analysis of socioeconomic inequities in EV charging infrastructure, highlighting correlations between household income, population density, and the number of EV charging stations.

2. **📓 Notebook**:  
   The Jupyter notebook ([`Notebook.ipynb`](./Notebook-Charging_Ahead_Socioeconomic_Inequities_in_Electric_Vehicle_Charging_Infrastructure_Across_the_United_States.ipynb)) includes the data cleaning, preparation, exploratory data analysis (EDA), and visualization steps. Key steps in the analysis:
   - 🔄 Cleaning and merging datasets on EV charging stations and socioeconomic factors.
   - 📊 Correlation and geospatial analysis of EV infrastructure distribution.
   - ⏳ Temporal trends and their relationship with income and population size.

3. **📊 Dataset**:  
   The cleaned and merged dataset ([`Dataset.csv`](./evc_income_merged.xlsx)) consolidates EV charging station data with socioeconomic indicators. It serves as the primary input for the analysis conducted in the notebook.

## 🌟 Key Highlights

- **📝 Abstract**:  
  Wealthier regions in the United States are significantly better equipped with EV charging stations, while economically disadvantaged areas face barriers to access. The study emphasizes the need for equitable infrastructure to foster inclusive adoption of sustainable transportation.

- **📈 Findings**:  
  - 📉 Positive correlation between the number of EV charging stations and household income.
  - ⏲️ Temporal trends show an increasing disparity in station deployment over time.
  - 👥 Population size is a stronger predictor of charging station availability than income at the state level.

- **📚 Data Sources**:  
  - EV Charging Stations: U.S. Department of Energy’s Alternative Fuels Data Center.  
  - Household Income: Kaggle dataset.  
  - Population Data: Wikipedia and publicly available resources.

## 🛠️ How to Use This Repository

1. **📄 Read the Paper**:  
   Start by reviewing the paper for detailed insights and methodologies.

2. **🔍 Explore the Notebook**:  
   Open the Jupyter notebook to see the step-by-step data analysis and visualizations.  
   - Prerequisites: Python, Jupyter, and the following libraries:
     ```
     pandas, numpy, matplotlib, seaborn, geopandas
     ```
   - Run the notebook locally or on a cloud platform (e.g., Google Colab).

3. **📊 Analyze the Dataset**:  
   Use the provided dataset for further analysis or to build predictive models.

## 🚀 Future Directions

- 🌍 Expand the analysis to include racial demographics and rural vs. urban divides.
- 🤖 Develop predictive models to identify underserved regions.
- 🛡️ Propose strategies to normalize infrastructure deployment based on population and geographic area.

## 📌 Citation

If you use this work, please cite:

```
Antebi, S., & Fire, M. (2024). Charging Ahead: Socioeconomic Inequities in Electric Vehicle Charging Infrastructure Across the United States.
```

## 📝 License

This project is licensed under the MIT License. See [`LICENSE`](./LICENSE) for details.

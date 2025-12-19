# DATS 2102 Final Project

## Project Overview
This project examines global development patterns from 2000–2023, focusing on relationships between economic capacity, poverty, life expectancy, renewable energy use, and population. The analysis emphasizes visual exploration and interpretation rather than causal inference, using a combination of exploratory analysis, results-driven visualizations, and an interactive mini-dashboard.

## Research Question
How are poverty rates and life expectancy associated with economic capacity across countries over time, and how does renewable energy adoption vary across these development pathways?

---

## Files Included
- `Final_Project.ipynb`: Main analysis notebook with narrative, code, and figures  
- `Final_Project.html`: Rendered HTML version of the notebook  
- `data/`: Folder containing all source datasets  
- `slides.pdf`: Slide deck for the final presentation  
- `demo_video.mp4`: Short recorded walkthrough of the project  

---

## Data Sources
This project uses publicly available international datasets from **Our World in Data**, which compiles and harmonizes data from institutions including the World Bank and the United Nations. All datasets were accessed in **December 2025**.

- **Population Estimates and Projections**  
  Source: Our World in Data (United Nations World Population Prospects)  
  URL: https://ourworldindata.org/grapher/population-with-un-projections  
  Description: Total population by country and year, including historical estimates and UN projections.  

- **Life Expectancy at Birth**  
  Source: Our World in Data (Human Mortality Database & UN World Population Prospects)  
  URL: https://ourworldindata.org/grapher/life-expectancy-hmd-unwpp  
  Description: Life expectancy at birth for the total population by country and year.  

- **Renewable Energy Consumption**  
  Source: Our World in Data  
  URL: https://ourworldindata.org/grapher/modern-renewable-energy-consumption  
  Description: Electricity generation from modern renewable sources by country and year.  

- **GDP per Capita (PPP)**  
  Source: Our World in Data (World Bank)  
  URL: https://ourworldindata.org/grapher/gdp-per-capita-worldbank  
  Description: Gross domestic product per capita adjusted for purchasing power parity, constant international dollars.  

- **Share of Population Living in Extreme Poverty**  
  Source: Our World in Data (World Bank)  
  URL: https://ourworldindata.org/explorers/poverty-explorer  
  Description: Percentage of the population living below the international extreme poverty line (approximately $3 per day, PPP-adjusted).  

---

## How to Run
1. Open `Final_Project.ipynb` in Jupyter.  
2. Ensure all CSV files are located in the `data/` directory.  
3. Restart the kernel and run all cells from top to bottom.  

All figures and interactive components will render automatically.

---

## Notes on Methods
- Global life expectancy trends are computed as population-weighted averages to account for differences in country size.  
- Country coverage varies across analyses due to differences in data availability across indicators and years.  
- Interactive components use Plotly and are designed for exploratory, user-driven analysis.  
- All visualizations use color-blind–safe palettes (e.g., Viridis), sufficient contrast, and do not rely on color alone to convey information.

---

## AI Assistance Disclosure
AI tools were used to assist with structuring the overall organization of the project, including the order of sections and the flow of information presented to the audience. AI assistance was also used for minor debugging related to the interactive Plotly-based dashboard, including adjustments to animation controls and figure layout to ensure proper rendering in HTML. All analysis decisions, interpretations, and final visualizations were independently completed by the author.
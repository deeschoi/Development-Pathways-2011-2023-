# Development Pathways (2011–2023): Poverty, Life Expectancy, Economic Capacity, and Renewable Electricity
<div align = "center">
  <img 
    width="695" 
    height="493" 
    alt="animation_screenshot" 
    src="https://github.com/user-attachments/assets/eee73dc6-e6eb-4eab-9a7e-072f4f6d4aee" 
  />
  <p><em>
    Static snapshot shown above: View the full animated visualization in the interactive notebook or HTML output.
  </em></p>
</div>

## Project Overview
This project explores global development patterns from 2000–2023 using publicly available data from the World Bank, United Nations, and related sources. It examines relationships between economic capacity, poverty, life expectancy, renewable energy consumption, and population change across countries and over time.

The analysis emphasizes visual exploration and interpretation rather than causal inference, using a combination of exploratory analysis, results driven visualizations, and an interactive mini dashboard. The primary goal is to communicate complex global trends clearly through well designed, theory informed data visualizations grounded in storytelling and visual perception principles.  

## Research Question
*How are poverty rates and life expectancy associated with economic capacity across countries over time, and how does renewable energy adoption vary across these development pathways?*

---

## Files Included
- `global_dev_viz.ipynb`: Main analysis notebook with narrative, code, and figures  
- `global_dev_viz.html`: Rendered HTML version of the notebook
- `global_dev_viz.qmd`: QMD file rendered from quarto
- `data/`: Folder containing all source datasets  
- `project_presentation.pdf`: Slide deck for the final presentation  

---

## Tools and Libraries
<div align="center">
  <img width="150" alt="python" src="https://github.com/user-attachments/assets/d2f3e707-b20f-4770-a6ad-4ba4dad3ea95" />
  <img width="150" alt="pandas" src="https://github.com/user-attachments/assets/21494d12-c145-4750-bb10-4d37756b5fbe" />
  <img width="150" alt="plotly" src="https://github.com/user-attachments/assets/235e4d59-62a4-46f7-a2f8-c30c5d97c4e5" />
  <img width="150" alt="matplotlib" src="https://github.com/user-attachments/assets/f16cc0f0-fc77-4106-a9d4-91d4ee31d80a" />
  <img width="150" alt="seaborn" src="https://github.com/user-attachments/assets/92139ea8-da09-429e-90bb-7f96414300de" />
  <img width="150" alt="jupyter" src="https://github.com/user-attachments/assets/8e3b56a7-34d1-4bad-a454-ad1f64930d0c" />
</div>

---

## Data Sources
This project uses publicly available international datasets from **Our World in Data**, which compiles and harmonizes data from institutions including the World Bank and the United Nations.

- Population estimates and projections (UN World Population Prospects)
- Life expectancy at birth (Human Mortality Database & UN WPP)  
- GDP per capita (adjusted, World Bank)
- Share of population living in extreme poverty (World Bank)
- Modern renewable electricity consumption

CSV files of each dataset can be found and downloaded from the `data` folder.

---

## How to Run
1. Open `global_dev_viz.ipynb` in Jupyter or VS Code.  
2. Ensure all CSV files are located in the `data/` directory.  
3. Restart the kernel and run all cells from top to bottom.  

All figures and interactive components will render automatically.

---

## Data Sources and Preparation  
To prepare for the analysis, the following steps were performed:
- Cleaning and filtering country-level time series data
- Harmonizing country identifiers across datasets
- Reshaping datasets into tidy formats suitable for visualization
- Aligning indicators across shared year ranges
- Handling missing values and inconsistent temporal coverage
- Accounting for differences in country size by computing population-weighted global life expectancy trends

Country coverage varies across analyses due to differences in data availability by indicator and year.

---

## Visualization Approach
### Design and Accessibility
All visualizations are designed with clarity, perception, and accessibility as core priorities. In particular:
- Color blind safe palettes (e.g., Viridis) are used throughout
- Sufficient contrast is maintained for readability
- Visuals do not rely on color alone to convey information; position, labels, and annotations are also used
- Consistent scales, axes, and encodings support accurate cross-country and temporal comparison

These choices ensure that the visualizations are interpretable by a wide audience and align with best practices in ethical data visualization.

### Narrative Structure
Visualizations are embedded within a structured narrative that progresses from broad global trends to more focused relationships between economic capacity, life expectancy, poverty, population change, and renewable energy use. Each visualization is designed to serve a specific communicative purpose rather than functioning as a standalone chart.

---

## Key Takeaways
- **Economic capacity, poverty reduction, and life expectancy are strongly linked**, with higher-income countries clustering at low poverty and high health outcomes
- **Economic growth supports health improvements but does not ensure uniform outcomes**, as countries with similar GDP per capita often exhibit markedly different life expectancy
- **Renewable electricity availability per capita generally increases with income**, but adoption varies widely among countries at similar income levels
- **Renewable energy is associated with broader development progress rather than acting as a direct driver of population health**, with a positive but diffuse relationship to life expectancy
- **Overall development trajectories are highly heterogeneous**, reinforcing the importance of examining multiple indicators together

---

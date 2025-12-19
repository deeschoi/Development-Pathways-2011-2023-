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

The analysis emphasizes visual exploration and interpretation rather than causal inference, using a combination of exploratory analysis, results driven visualizations, and an interactive mini dashboard. The primary goal is to communicate complex global trends clearly and effectively through well designed, theory informed data visualizations grounded in storytelling and visual perception principles.  

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
<a href="https://www.python.org"><img src="https://github.com/user-attachments/assets/b2208695-3b7f-4507-9c8d-02a14f07341d" width="150" height = "70" alt="Python" /></a>
<a href="https://pandas.pydata.org"><img src="https://github.com/user-attachments/assets/38500205-8d85-4b46-8b2b-9222a24c611c" width="150" height = "70" alt="pandas" /></a>
<a href="https://matplotlib.org"><img src="https://github.com/user-attachments/assets/06175adf-fa77-4969-abda-7b181667bb79" width="150" height = "70" alt="matplotlib" /></a>
<a href="https://seaborn.pydata.org"><img src="https://github.com/user-attachments/assets/e090b466-3c57-4bc5-83c0-1048b7fc67f4" width="150" height = "70" alt="seaborn" /></a>
<a href="https://plotly.com/python/"><img src="https://github.com/user-attachments/assets/7e7ccd3a-5667-46cc-8778-180396e01c29" width="150" height = "70" alt="Plotly" /></a>
<a href = "https://jupyter.org/"><img src = "https://github.com/user-attachments/assets/7ed802c0-b5c3-4a27-89ec-f7bad3901830" width = "150" height = "70" alt = "Jupyter" /><a>

---

## Data Sources
This project uses publicly available international datasets from **Our World in Data**, which compiles and harmonizes data from institutions including the World Bank and the United Nations.

- Population estimates and projections (UN World Population Prospects)
- Life expectancy at birth (Human Mortality Database & UN WPP)  
- GDP per capita (adjusted, World Bank)
- Share of population living in extreme poverty (World Bank)
- Modern renewable electricity consumption

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

The notebook intentionally combines exploratory and explanatory visualizations, using interactive elements to support user-driven exploration while maintaining a clear narrative structure.

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

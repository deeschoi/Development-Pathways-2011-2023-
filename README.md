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

## Methods and Tools
### Data Sources and Preparation  
To prepare for the analysis, the following steps were performed:
- Cleaning and filtering country-level time series data
- Harmonizing country identifiers across datasets
- Reshaping datasets into tidy formats suitable for visualization
- Aligning indicators across shared year ranges
- Handling missing values and inconsistent temporal coverage
- Accounting for differences in country size by computing population-weighted global life expectancy trends

Country coverage varies across analyses due to differences in data availability by indicator and year.

### Tools and Libraries
<div align="center">
  <table cellpadding="0" cellspacing="0">
    <tr>
      <td align="center">
        <img width="120" alt="python_logo"
             src="https://github.com/user-attachments/assets/5c41857a-1651-445a-a16e-1e7015fca7ac" />
      </td>
      <td align="center">
        <img width="120" alt="pandas_logo"
             src="https://github.com/user-attachments/assets/e1977ef0-d99c-4131-b46c-f70d37e9e968" />
      </td>
      <td align="center">
        <img width="120" alt="matplotlib_logo"
             src="https://github.com/user-attachments/assets/f8d3c767-eb70-471e-aaaa-bea278712c7d" />
      </td>
      <td align="center">
        <img width="120" alt="seaborn_logo"
             src="https://github.com/user-attachments/assets/5001879f-bbeb-4108-b781-baeafd11d1e9" />
      </td>
      <td align="center">
        <img width="120" alt="plotly_logo"
             src="https://github.com/user-attachments/assets/4e6ff38b-861d-4b89-a747-3400d24dbb85" />
      </td>
      <td align="center">
        <img width="120" alt="jupyter_logo"
             src="https://github.com/user-attachments/assets/d31433ad-b9a7-4bb2-aedd-cf916e8c98fd" />
      </td>
    </tr>
  </table>
</div>


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

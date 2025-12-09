# Lepidoptera Taxonomy

This repository contains an R Markdown project for visualizing taxonomic data of Lepidoptera (butterflies and moths). The project reads an Excel dataset of Lepidoptera families and generates multiple visualizations to explore taxonomic hierarchy, structure, and distribution. Taxonomic information was extracted from publicly available records on BugGuide.net.

## Files

- `LepFamiliesOnly.xlsx`: Excel file containing curated Lepidoptera taxonomy with columns: `SUPERFAMILY`, `FAMILY`, `SUBFAMILY`, `Tribe`.
- `Lepidoptera_Visualizations.Rmd`: R Markdown script with all visualization code.

## Visualizations Included

1. **Bar Plot** – Counts of families per superfamily  
2. **Tree Graph** – Hierarchical representation of taxonomic levels  
3. **Treemap** – Distribution of families within superfamilies  
4. **Network Graph** – Connections among superfamilies, families, subfamilies, and tribes  
5. **Interactive Plotly Bar Chart** – Family counts by superfamily  
6. **Collapsible Tree** – Zoomable, interactive hierarchical tree  
7. **Interactive Treemap (Plotly)** – Interactive distribution of families across superfamilies  

## FAIR and CARE Principles

This project follows open-science practices and aligns with established FAIR and CARE guidelines.

### FAIR
- **Findable:** Clear file naming, metadata, and repository tags support discoverability.  
- **Accessible:** Data and code are openly available and fully reproducible through the R Markdown file.  
- **Interoperable:** Uses standard taxonomic fields and common data formats (`.xlsx`, `.csv`, `.Rmd`).  
- **Reusable:** Documentation, metadata, and open licensing enable broad reuse and integration into future research.

### CARE
Although the dataset contains no culturally sensitive information, the repository aligns with CARE principles:  
- **Collective Benefit:** Developed for education, research, and community use.  
- **Authority to Control:** Contains only publicly available, non-sensitive taxonomic data with clear attribution.  
- **Responsibility:** Transparent sourcing ensures responsible data use.  
- **Ethics:** No Indigenous knowledge or restricted data are included.

## Dependencies

This project requires the following R packages:

- `readxl`  
- `ggplot2`  
- `igraph`  
- `ggraph`  
- `treemapify`  
- `dplyr`  
- `tidyr`  
- `plotly`  
- `collapsibleTree`

Install missing packages with:

```r
install.packages(c(
  "readxl", "ggplot2", "igraph", "ggraph",
  "treemapify", "dplyr", "tidyr", "plotly", "collapsibleTree"
))

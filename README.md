#LepidopteraTaxonomy

This repository contains an R Markdown project for visualizing taxonomic data of Lepidoptera (butterflies and moths). The project reads an Excel dataset of Lepidopteran families and generates multiple visualization types to explore taxonomic structure and relative diversity across hierarchical levels.

#Files
	•	LepFamiliesOnly.xlsx — Curated Lepidoptera taxonomy with fields for SUPERFAMILY, FAMILY, SUBFAMILY, and Tribe. Taxonomic information was extracted from publicly available records on BugGuide.net.
	•	Lepidoptera_Visualizations.Rmd — R Markdown script containing all visualization code.

#Visualizations Included
	•	Bar plot: counts of families per superfamily
	•	Tree graph: hierarchical visualization of taxonomic relationships
	•	Treemap: relative distribution of families within superfamilies
	•	Network graph: connections among superfamilies, families, subfamilies, and tribes
	•	Interactive Plotly bar chart: family abundance by superfamily
	•	Collapsible tree: zoomable exploration of taxonomic hierarchy
	•	Interactive Plotly treemap: dynamic family-level patterns

#FAIR and CARE Principles
This project follows open-science practices and aligns with established FAIR and CARE guidelines.
#FAIR
	•	Findable: Clear naming, metadata, versioning, and repository tags support discoverability.
	•	Accessible: Data and code are openly available; visualizations can be fully reproduced through the R Markdown file.
	•	Interoperable: Data fields follow standard taxonomic structure and are provided in widely used formats (.xlsx, .csv, .Rmd).
	•	Reusable: Documentation, metadata, and open licensing enable broad reuse.

#CARE
Although the dataset contains no Indigenous knowledge or sensitive cultural information, the repository aligns with CARE principles:
	•	Collective Benefit: Designed for research, education, and community use.
	•	Authority to Control: Uses only publicly available, non-sensitive taxonomic data with transparent sourcing.
	•	Responsibility: Proper attribution ensures responsible use.
	•	Ethics: No restricted or community-derived knowledge is included.

#Dependencies
Required R packages:
readxl, ggplot2, igraph, ggraph, treemapify, dplyr, tidyr, plotly, collapsibleTree

#Usage
	1.	Clone or download the repository.
	2.	Open Lepidoptera_Visualizations.Rmd in RStudio.
	3.	Update the dataset path if needed:
lep_data <- read_excel("/path/to/LepFamiliesOnly.xlsx")
	4.	Knit the R Markdown file to generate the HTML visualization output.

#Notes
	•	Interactive components require HTML output.
	•	The dataset must retain the column structure: SUPERFAMILY, FAMILY, SUBFAMILY, Tribe.
	•	The project focuses on exploratory visualization of taxonomic hierarchies.

#License
Released under the MIT License.
See the LICENSE file for full terms.

#Still to Do
	•	Add images for families, subfamilies, and tribes
	•	Incorporate diagnostic features or trait information
	•	Improve layout and interactivity of network and hierarchical visualizations

Author
Angela Robles
Environmental Sciences Graduate Student

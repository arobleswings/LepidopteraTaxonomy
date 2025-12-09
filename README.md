# LepidopteraTaxonomy

Lepidoptera Taxonomy
This repository contains an R Markdown project for visualizing taxonomic data of Lepidoptera (butterflies and moths). The project reads an Excel dataset of Lepidopteran families and generates multiple visualization types to explore taxonomic structure and relative diversity across hierarchical levels.

Files
LepFamiliesOnly.xlsx: Excel file containing curated Lepidoptera taxonomy, with fields for SUPERFAMILY, FAMILY, SUBFAMILY, and Tribe. Taxonomic information was extracted from publicly available records on BugGuide.net.
Lepidoptera_Visualizations.Rmd: R Markdown script containing all visualization code.

Visualizations Included
Bar Plot – Counts of families per superfamily.
Tree Graph – Hierarchical visualization of taxonomic relationships.
Treemap – Relative distribution of families within superfamilies.
Network Graph – Connections among superfamilies, families, subfamilies, and tribes.
Interactive Plotly Bar Chart – Interactive family abundance by superfamily.
Collapsible Tree – Zoomable, interactive exploration of taxonomic hierarchy.
Interactive Treemap (Plotly) – Dynamic visualization of family-level patterns.

FAIR and CARE Principles
This project is developed using open-science practices and follows established FAIR and CARE guidelines.
FAIR:
Findable: Files include clear naming, metadata, and versioning. Repository tags and keywords support discoverability.
Accessible: Data and code are openly available without access barriers; all visualizations can be reproduced using the provided R Markdown file.
Interoperable: Data fields follow standard taxonomic structures and are provided in widely usable formats (.xlsx, .csv, .Rmd).
Reusable: Documentation, metadata, and an open license facilitate reuse, adaptation, and integration into other research or educational workflows.
CARE:
Although the dataset contains no Indigenous knowledge or culturally sensitive information, the repository aligns with CARE principles.
Collective Benefit: Outputs are designed for education, research, and community use.
Authority to Control: Only publicly available, non-sensitive taxonomic data are included, and all sources are transparently documented.
Responsibility: Proper attribution and sourcing support responsible data use.
Ethics: No community-derived or restricted knowledge is included.

Dependencies
The project requires the following R packages: readxl, ggplot2, igraph, ggraph, treemapify, dplyr, tidyr, plotly, collapsibleTree.

Usage
Clone or download this repository.
Open Lepidoptera_Visualizations.Rmd in RStudio.
Adjust the dataset path if needed:
lep_data <- read_excel(”/path/to/LepFamiliesOnly.xlsx”)
Knit the R Markdown file to generate the full HTML visualization output.

Notes
Interactive content requires HTML output to function correctly.
The dataset must retain the column structure SUPERFAMILY, FAMILY, SUBFAMILY, Tribe for full compatibility.
The project focuses on exploratory visualization of taxonomic hierarchies.

License
This project is released under the MIT License.
See the LICENSE file for full terms.

Still to Do
Integrate images for families, subfamilies, and tribes.
Add diagnostic features or trait information for each taxonomic level.
Enhance interactivity and layout of network and hierarchical plots.

Author
Angela Robles
Environmental Sciences Graduate Student


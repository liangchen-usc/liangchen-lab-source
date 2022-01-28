---
title: "Quantile regression for challenging cases of eQTL mapping"
authors:
- Bo Sun
- Liang Chen
author_notes:
- 
- "corresponding author"
date: "2019-11-01T00:00:00Z"
doi: "https://doi.org/10.1093/bib/bbz097"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Briefings in Bioinformatics"
publication_short: ""

abstract: Mapping of expression quantitative trait loci (eQTLs) facilitates interpretation of the regulatory path from genetic variants to their associated disease or traits. High-throughput sequencing of RNA (RNA-seq) has expedited the exploration of these regulatory variants. However, eQTL mapping is usually confronted with the analysis challenges caused by overdispersion and excessive dropouts in RNA-seq. The heavy-tailed distribution of gene expression violates the assumption of Gaussian distributed errors in linear regression for eQTL detection, which results in increased Type I or Type II errors. Applying rank-based inverse normal transformation (INT) can make the expression values more normally distributed. However, INT causes information loss and leads to uninterpretable effect size estimation. After comprehensive examination of the impact from overdispersion and excessive dropouts, we propose to apply a robust model, quantile regression, to map eQTLs for genes with high degree of overdispersion or large number of dropouts. Simulation studies show that quantile regression has the desired robustness to outliers and dropouts, and it significantly improves eQTL mapping. From a real data analysis, the most significant eQTL discoveries differ between quantile regression and the conventional linear model. Such discrepancy becomes more prominent when the dropout effect or the overdispersion effect is large. All the results suggest that quantile regression provides more reliable and accurate eQTL mapping than conventional linear models. It deserves more attention for the large-scale eQTL mapping.

# Summary. An optional shortened abstract.
# summary: 

tags:
- Phd Student paper
featured: true

# links:
# - name: "link"
#   url: "https://www.mdpi.com/2073-4409/10/11/2901/htm"
url_pdf: https://academic.oup.com/bib/article-abstract/21/5/1756/5583704?redirectedFrom=fulltext
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Desired robustness of quantile regression.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

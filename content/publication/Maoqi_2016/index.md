---
title: "An empirical likelihood ratio test robust to individual heterogeneity for differential expression analysis of RNA-seq"
authors:
- Maoqi Xu
- Liang Chen
author_notes:
- 
- "corresponding author"
date: "2016-10-01T00:00:00Z"
doi: "https://doi.org/10.3390/cells10112901"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Briefings in Bioinformatics"
publication_short: ""

abstract: The individual sample heterogeneity is one of the biggest obstacles in biomarker identification for complex diseases such as cancers. Current statistical models to identify differentially expressed genes between disease and control groups often overlook the substantial human sample heterogeneity. Meanwhile, traditional nonparametric tests lose detailed data information and sacrifice the analysis power, although they are distribution free and robust to heterogeneity. Here, we propose an empirical likelihood ratio test with a mean–variance relationship constraint (ELTSeq) for the differential expression analysis of RNA sequencing (RNA-seq). As a distribution-free nonparametric model, ELTSeq handles individual heterogeneity by estimating an empirical probability for each observation without making any assumption about read-count distribution. It also incorporates a constraint for the read-count overdispersion, which is widely observed in RNA-seq data. ELTSeq demonstrates a significant improvement over existing methods such as edgeR, DESeq, t-tests, Wilcoxon tests and the classic empirical likelihood-ratio test when handling heterogeneous groups. It will significantly advance the transcriptomics studies of cancers and other complex disease.

# Summary. An optional shortened abstract.
# summary: 

tags:
- Phd Student paper
featured: false

# links:
# - name: "link"
#   url: "https://www.mdpi.com/2073-4409/10/11/2901/htm"
url_pdf: https://academic.oup.com/bib/article/19/1/109/2566854
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
  caption: 'Power difference between DESeq and ELTSeq'
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
Click the *Cite* button above to import publication metadata.
{{% /callout %}}

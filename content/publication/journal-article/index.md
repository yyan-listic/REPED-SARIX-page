---
title: 'Robust Phase Linking in InSAR'
authors:
  - 'Phan Viet Hoa Vu'
  - 'Arnaud Breloy'
  - 'Frédéric Brigui'
  - admin
  - 'Guillaume Ginolhac'
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2023-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'In *IEEE Transactions in Geosciences and Remote Sensing*'
publication_short: 'In *TGRS*'

abstract: > 
Phase linking is a prominent methodology to estimate coherence and phase difference in interferometric synthetic aperture radar. This method is driven by a maximum likelihood estimation approach, which allows to fully exploit all the possible interferograms from a time series. Its performance is, however, known to be affected by the accuracy of the covariance matrix estimation step, which usually requires to introduce additional prior information on its structure when there is a small sample support (spatial window). Moreover, most phase linking algorithms are built upon the sample covariance matrix, due to the assumption of an underlying Gaussian distribution. In a scenario where SAR data is high resolution, or when the study area is spatially heterogeneous (e.g., urban area), this assumption can also limit the accuracy of the covariance matrix estimation step. Considering the two aforementioned issues, we introduce alternative statistical models, whose maximum likelihood estimators then yield new phase linking algorithms. In order to be robust to non-Gaussian data, we consider the use of a more general model of scaled mixture of Gaussian. To address small sample support issues, we also generalize this approach to a possibly low-rank structured covariance matrix. A unified algorithm to perform phase linking given these models is then derived and validated by simulations and a real data case (Sentinel-1 data).

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
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
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).

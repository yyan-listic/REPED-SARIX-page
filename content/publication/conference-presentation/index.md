---
title: 'Improving ice thickness estimation of glaciers using deep learning methods : a case study in the Swiss Alps'
authors:
  - Lorenzo Lopez-Uroz
  - admin
  - Alexandre Benoit
  - Antoine Rabatel
  - Amaury Dehecq
  - Sophie Giffard-Roisin
date: '2023-04-28T00:00:00Z'
doi: 'https://doi.org/10.5194/egusphere-egu23-8339'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-28-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['0']

# Publication name and optional abbreviated publication name.
publication: In **EGU General Assembly 2023**
publication_short: In **EGU2023**

abstract: Accurate estimation of ice thickness is essential for understanding and predicting the behaviors of glaciers, since the ice thickness provides valuable information about the glacier state and helps anticipate the evolution of whole glaciers systems. This latter knowledge is particularly important given the fact that glaciers act as natural reservoirs in the global water cycle. They are also indicators of the current and past state of global and local climate, as the properties and dynamics of glaciers reveal insights into the environmental conditions they have experienced.

Current methods for estimating ice thickness face issues : field measurements such as the Ground Penetrating Range method can be costly and may not provide dense, continuous, renewable coverage. On the other hand, methods based on physical modeling can be computationally intensive and are dependent on assumptions about model parameters that may be unreliable in a poorly understood context. Results may thus be sensitive to the choice of prior information and prone to bias when working with limited or noisy data.

Deep learning methods provide a promising solution for ice thickness prediction. One key advantage is their ability to handle large, multi-dimensional datasets and to learn directly from raw data without prior knowledge. Additionally, deep learning models are able to exploit non-linear relationships between datasets. Using such models also allows simultaneous training of other tasks, such as terrain classification to identify the presence of glaciers when it is not provided or outdated. In this study, we propose the use of such an approach relying on convolutional models based on VGGNet, ResNet and U-Net.

Our goal is to obtain an accurate estimation of the glacier thickness distribution. We propose the use of neural networks in order to 1) be free from statistical/physical assumptions, 2) leverage deep relationships between observed data and physical parameters to be estimated, 3) overcome inaccuracies in collected data, and 4) accurately represent complex patterns such as non-linear thickness variations within the glacier. Additionally, it is important that these models should not be prone to common issues of deep learning such as overfitting and lack of explainability.

We conduct our study on Alpine glaciers in Switzerland. The input data for our neural network models includes: 1) average ice velocity fields calculated from correlation of Sentinel-2 images with a resolution of 50 metres, and 2) altitudes and slopes derived from the Swiss digital elevation model with a resolution of 10 metres. To verify the accuracy of the predicted ice thickness values, we use ground truth data obtained from GPR surveys conducted in profile form, from 2012 to 2021.

In addition to estimating the ice thickness, we also perform direct classification of glaciers vs. non-glacier areas. Results demonstrate the feasibility of quickly training a neural network model with limited training data and producing stable, high-quality ice thickness estimates for different glaciers in the study region.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Source Themes
featured: true

links:
  - name: Custom Link
    url: https://doi.org/10.5194/egusphere-egu23-8339
url_pdf: ''
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---



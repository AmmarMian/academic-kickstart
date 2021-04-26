---
title: "Designing SAR Images Change-point Estimation Strategies Using an Mse Lower Bound"
authors:
- admin
- Lucien Bacharach
- Guillaume Ginolhac
- Alexandre Renaux
- Mohammed Nabil El Korso
- Jean-Philippe Ovarlez
author_notes:
- "Main contributions"
- "Main contributions"
date: "2019-05-12"
doi: "10.1109/ICASSP.2019.8682875"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*
publication_short: In *ICASSP 2019*

abstract: A growing problem in the remote sensing community concerns the estimation of change-points in a time series of Synthetic Aperture Radar (SAR) images. Although the methodologies of change-point estimation have already been investigated in the literature, there are, to the best of our knowledge, no study on the expected performance for the estimation of change-points in a Wishart distributed time series. This is mainly due to the fact that few results exist on change-point estimation performance in the mathematical literature the classical central limit theorem does not apply and the classical Cramer-Rao Bound does not exist due to the discrete nature of the parameters. To fill this gap, this paper proposes to use a lower-bound on the Mean Square Error (MSE) with fewer regularity conditions. To this end, recent works on hybrid Cramer-Rao/Weiss-Weinstein bound have been adapted to the specific SAR problematic of interest. Since estimation strategies usually rely on a set of parameters which have to be set by the user, we show how the proposed lower bound allows performing an appropriate tuning. Moreover, the proposed bound is computationally efficient which enables an extensive analysis without a high computational cost.

# Summary. An optional shortened abstract.
summary: Hybrid Cramer-Rao/Weiss-Weinstein bound for SAR applications.

tags: [Lower-Bounds, Change-point estimation, Ph.D]
featured: true

links:
url_pdf: pdf/icassp_paper_2019.pdf
url_code: ''
url_dataset: ''
url_poster: 'pdf/icassp_poster_2019.pdf'
url_project: 'http://am.atto.free.fr/index_phoenix.htm'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
# slides: example
---



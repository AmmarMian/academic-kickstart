---
title: "Contributions to SAR Image Time Series Analysis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin


date: "2019-09-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-03T15:15:01Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Remote sensing data from Synthetic Aperture Radar (SAR) sensors offer a unique opportunity to record, to analyze, and to predict the evolution of the Earth. In the last decade, numerous satellite remote sensing missions have been launched (Sentinel-1, UAVSAR, TerraSAR X, etc.). This resulted in a dramatic improvement in the Earth image acquisition capability and accessibility. The growing number of observation systems allows now to build high temporal/spatial-resolution Earth surface images data-sets. This new scenario significantly raises the interest in time-series processing to monitor changes occurring over large areas. However, developing new algorithms to process such a huge volume of data represents a current challenge. In this context, the present thesis aims at developing methodologies for change detection in high-resolution SAR image time series.These series raise two notable challenges that have to be overcome:On the one hand, standard statistical methods rely on multivariate data to infer a result which is often superior to a monovariate approach. Such multivariate data is however not always available when it concerns SAR images. To tackle this issue, new methodologies based on wavelet decomposition theory have been developed to fetch information based on the physical behavior of the scatterers present in the scene.On the other hand, the improvement in resolution obtained from the latest generation of sensors comes with an increased heterogeneity of the data obtained. For this setup, the standard Gaussian assumption used to develop classic change detection methodologies is no longer valid. As a consequence, new robust methodologies have been developed considering the family of elliptical distributions which have been shown to better fit the observed data.The association of both aspects has shown promising results in change detection applications.


tags: [Robust statistics, Covariance homogeneity, Low-rank, Change-point estimation, Synthetic Aperture Radar, Change detection, Lower-bounds, Riemannian geometry, Machine learning, Ph.D]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://tel.archives-ouvertes.fr/tel-02464840/document'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'talks/These.pdf'
url_source: ''
url_video: ''

projects:
- change-detection

---

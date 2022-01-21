---
title: "Authorized Patent: Clustering Enabled Few-shot load forecasting method and its device"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zhihui Chen
- South China Power Grid Co Ltd

# Author notes (optional)
author_notes:
- "Inventor"
- "Inventor"
- "Applicant"

date: "2021-11-20"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: In the official announcement stage of the *China National Copyright Administration* 
publication_short: In the official announcement stage
abstract: The application discloses the scarce sample load forecasting method and prediction device based on clustering. The forecasting method includes feature extraction of historical power load and target samples to obtain feature vector; According to the feature vector, the historical data and the target sample are ensemble-clustered to obtain a stable result. The wavelet denoising algorithm was used to de-noise the clustering results, and the data after denoising were averaged to obtain the time series data of preset length. The time-series data of preset length includes historical time series data and time-series data to be forecasted. The time-series data with preset lengths are input into the two-phase LSTM neural network to obtain the forecasting results of power load. The historical sequence is used to train the second-order LTSM neural network, and the target data is used to adjust the two-phase LTSM neural network in novel tasks. This application still has excellent forecast performance under the condition of a limited training set.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---




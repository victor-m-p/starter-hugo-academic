---
title: 'Inferring Cultural Landscapes with the Inverse Ising Model '

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Simon DeDeo

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-01-31T00:00:00Z'
doi: 'https://doi.org/10.3390/e25020264'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-21T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Entropy*
publication_short: In *Entropy*

abstract: The space of possible human cultures is vast, but some cultural configurations are more consistent with cognitive and social constraints than others. This leads to a “landscape” of possibilities that our species has explored over millennia of cultural evolution. However, what does this fitness landscape, which constrains and guides cultural evolution, look like? The machine-learning algorithms that can answer these questions are typically developed for large-scale datasets. Applications to the sparse, inconsistent, and incomplete data found in the historical record have received less attention, and standard recommendations can lead to bias against marginalized, under-studied, or minority cultures. We show how to adapt the minimum probability flow algorithm and the Inverse Ising model, a physics-inspired workhorse of machine learning, to the challenge. A series of natural extensions—including dynamical estimation of missing data, and cross-validation with regularization—enables reliable reconstruction of the underlying constraints. We demonstrate our methods on a curated subset of the Database of Religious History; records from 407 religious groups throughout human history, ranging from the Bronze Age to the present day. This reveals a complex, rugged, landscape, with both sharp, well-defined peaks where state-endorsed religions tend to concentrate, and diffuse cultural floodplains where evangelical religions, non-state spiritual practices, and mystery religions can be found.

# Summary. An optional shortened abstract.
summary: We present an improved method to estimate a landscape model on biased and inconsistent data in the "small data" limit. We demonstrate the method on a curated subset of the Database of Religious History.

tags: [Machine Learning, Physics, Cultural Evolution, Inverse Ising Model, Minimum Probability Flow, Regularization, Cross-Validation, Missing Data, Database of Religious History, Religious History]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_article: 'https://www.mdpi.com/1099-4300/25/2/264'
url_cite: # this works 
url_code: 'https://github.com/victor-m-p/cultural-landscapes'
#url_slides: '' # insert slides here 
url_video: 'https://www.youtube.com/live/Zbh8GEkG0Uk?feature=share'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '' # insert a picture. 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
---
title: 'Efficient optimization of ODE neuron models using gradient descent'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Konrad Kording

# Author notes (optional)
author_notes:
  - ''

date: '2024-07-04T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2407.04025'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: ''

abstract: Neuroscientists fit morphologically and biophysically detailed neuron simulations to physiological data, often using evolutionary algorithms. However, such gradient-free approaches are computationally expensive, making convergence slow when neuron models have many parameters. Here we introduce a gradient-based algorithm using differentiable ODE solvers that scales well to high-dimensional problems. GPUs make parallel simulations fast and gradient calculations make optimization efficient. We verify the utility of our approach optimizing neuron models with active dendrites with heterogeneously distributed ion channel densities. We find that individually stimulating and recording all dendritic compartments makes such model parameters identifiable. Identification breaks down gracefully as fewer stimulation and recording sites are given. Differentiable neuron models, which should be added to popular neuron simulation packages, promise a new era of optimizable neuron models with many free parameters, a key feature of real neurons.

# Summary. An optional shortened abstract.
summary: Training morphologically and biophysically detailed neuron models is computationally expensive. Here we demonstrate through implementation of neuron simulations in PyTorch that the gradient-based backpropagation of error algorithm can be used to efficiently optimize such models.

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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---


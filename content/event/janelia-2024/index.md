---
title: Efficient optimization of ODE neurons using gradient descent

url: /optimization-ode-neurons-janelia/
event: Janelia Computation and Theory Seminar
event_url: https://www.janelia.org/our-research/computation-and-theory

location: Ashburn, Virginia
address:
  street: '19700 Helix Drive'
  city: Ashburn
  region: Virginia
  postcode: '20147'
  country: USA

summary: 'Speaker for the Computation and Theory Seminar at the Janelia Research Campus'
abstract: 'Neuroscientists fit simulations of morphologically and biophysically detailed neurons to data, often using evolutionary algorithms. However, such gradient-free approaches are computationally expensive, making convergence slow when neuron models have many parameters. Here we introduce a gradient-based algorithm using differentiable ODE solvers that scales well to high-dimensional problems. GPUs make parallel simulations fast and gradient calculations make optimization fast. We verify the usefulness of our approach optimizing neuron models with active dendrites with heterogeneously distributed ion channel densities. We find that individually stimulating and recording all dendritic compartments makes such models identifiable. Identification breaks down gracefully as less stimulation and recording sites are given. Differentiable neuron models, which should be added to popular neuron simulation packages, promise a new era of optimizable neuron models with many free parameters, a key feature of real neurons.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-05-16T10:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors: 
  - admin
  - Konrad Kording
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'My point of view before the seminar'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/IlennaJ
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Presentation at HHMI Janelia's Computation and Theory Seminar at the Janelia Research Campus on May 16th, 2024.
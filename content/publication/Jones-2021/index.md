---
title: 'Might a Single Neuron Solve Interesting Machine Learning Problems Through Successive Computations on Its Dendritic Tree?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Konrad Kording

# Author notes (optional)
author_notes:
  - ''

date: '2021-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Neural Computation
publication_short: ''

abstract: Physiological experiments have highlighted how the dendrites of biological neurons can nonlinearly process distributed synaptic inputs. However, it is unclear how aspects of a dendritic tree, such as its branched morphology or its repetition of presynaptic inputs, determine neural computation beyond this apparent nonlinearity. Here we use a simple model where the dendrite is implemented as a sequence of thresholded linear units. We manipulate the architecture of this model to investigate the impacts of binary branching constraints and repetition of synaptic inputs on neural computation. We find that models with such manipulations can perform well on machine learning tasks, such as Fashion MNIST or Extended MNIST. We find that model performance on these tasks is limited by binary tree branching and dendritic asymmetry and is improved by the repetition of synaptic inputs to different dendritic branches. These computational experiments further neuroscience theory on how different dendritic properties might determine neural computation of clearly defined tasks.

# Summary. An optional shortened abstract.
summary: It is unclear how qualitative dendritic properties contribute to neural computation beyond nonlinearity. We investigate the impact of thee properties in a neuron model derived from an artificial neural network. We find that these properties can negatively and positively impact performance on benchmark computer vision tasks. This opens questions about the potentially beneficial inductive biases that dendritic properties might introduce to a learning and computing model. Previously titled /"Can a Single Neuron Solve MNIST?/"

tags: []

# Display this page in the Featured widget?
featured: false

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

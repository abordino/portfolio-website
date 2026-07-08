---
title: 'Direct and efficient estimation of bilinear forms in staggered tensor panels'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - T. B. Berrett
  - Olga Klopp

date: '2026-07-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Preprint arXiv:2607.06330. R code used for the simulations is available [here](https://github.com/abordino/FunctionalCausalTensor)
publication_short: Preprint arXiv:2607.06330. R code used for the simulations is available [here](https://github.com/abordino/FunctionalCausalTensor)

abstract: We study the estimation of bilinear forms from noisy, partially observed tensor data. The signal follows a Tucker2 model, with shared unit and time factors across tensor layers and slice-specific cores. The missingness pattern is structured and motivated by staggered adoption designs, which are common in causal inference and related applications. We first analyse the four-block missingness pattern, the basic building block for general staggered adoption, and propose a spectral algorithm that pools information across layers and targets the functional directly, rather than completing the entire tensor. We prove a non-asymptotic mean squared error bound that exhibits a phase transition in the number of layers, showing when pooling improves estimation, and match it with a local minimax lower bound up to constants. We then extend the construction to general staggered adoption designs via an anchored four-block reduction, and derive analogous theoretical guarantees. Finally, we validate our theoretical findings through experiments on both simulated and real-world datasets.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/BilTensor.pdf'
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
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
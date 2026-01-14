---
title: ' Nonparametric inference for ratios of densities via uniformly valid and powerful permutation tests'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - T. B. Berrett

date: '2026-01-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Preprint arXiv:2505.24529. The accompanying **R** package **DRPT** is available from [CRAN](https://cran.r-project.org/web/packages/DRPT/index.html). R code used for the simulations is available [here](https://github.com/abordino/DRPT)
publication_short: Preprint arXiv:2505.24529. The accompanying **R** package **DRPT** is available from [CRAN](https://cran.r-project.org/web/packages/DRPT/index.html). R code used for the simulations is available [here](https://github.com/abordino/DRPT)

abstract: We propose the density ratio permutation test, a hypothesis test that assesses whether the ratio between two densities is proportional to a known function based on independent samples from each distribution. The test uses an efficient Markov Chain Monte Carlo scheme to draw weighted permutations of the pooled data, yielding exchangeable samples and finite sample validity. For power, if the statistic is an integral probability metric, our procedure is consistent under mild assumptions on the defining function class; specializing to a reproducing kernel Hilbert space, we introduce the shifted maximum mean discrepancy and prove minimax optimality of our test when a normalized difference between the densities lies in a Sobolev ball. We extend to the case of an unknown density ratio by estimating it on an independent training sample and derive type~I error bounds in terms of the estimation error as well as power results. This allows adapting our method to conditional two sample testing, making it a versatile tool for assessing covariate-shift and related assumptions, which frequently arise in transfer learning and causal inference. Finally, we validate our theoretical findings through experiments on both simulated and real-world datasets.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/DRPT.pdf'
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
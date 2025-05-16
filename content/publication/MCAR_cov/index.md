---
title: ' Tests of Missing Completely At Random based on sample covariance matrices'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - T. B. Berrett

date: '2024-06-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: The Annals of Statistics, *to appear*. I contributed to the R-package [MCARtest](https://cran.r-project.org/web/packages/MCARtest/index.html)
publication_short: The Annals of Statistics, *to appear*. I contributed to the R-package [MCARtest](https://cran.r-project.org/web/packages/MCARtest/index.html)

abstract: We study the problem of testing whether the missing values of a potentially high-dimensional dataset are Missing Completely at Random (MCAR). We relax the problem of testing MCAR to the problem of testing the compatibility of a collection of covariance matrices, motivated by the fact that this procedure is feasible when the dimension grows with the sample size. Our first contributions are to define a natural measure of the incompatibility of a collection of correlation matrices, which can be characterised as the optimal value of a Semi-definite Programming (SDP) problem, and to establish a key duality result allowing its practical computation and interpretation. By analysing the concentration properties of the natural plug-in estimator for this measure, we propose a novel hypothesis test, which is calibrated via a bootstrap procedure and demonstrates power against any distribution with incompatible covariance matrices. By considering key examples of missingness structures, we demonstrate that our procedures are minimax rate optimal in certain cases. We further validate our methodology with numerical simulations that provide evidence of validity and power, even when data are heavy tailed. Furthermore, tests of compatibility can be used to test the feasibility of positive semi-definite matrix completion problems with noisy observations, and thus our results may be of independent interest.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/mcar_cov.pdf'
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
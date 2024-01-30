---
title: 'Trigonometric Quadrature Fourier Features for Scalable Gaussian Process Regression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Max Balakirsky
  - Simon Mak

# Author notes (optional)

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 27th International Conference on Artificial Intelligence and Statistics
publication_short: In *AISTAT*

abstract: Fourier feature approximations have been successfully applied in the literature for scalable Gaussian Process (GP) regression. In particular, Quadrature Fourier Features (QFF) derived from Gaussian quadrature rules have gained popularity in recent years due to their improved approximation accuracy and better calibrated uncertainty estimates compared to Random Fourier Feature (RFF) methods. However, a key limitation of QFF is that its performance can suffer from well-known pathologies related to highly oscillatory quadrature, resulting in mediocre approximation with limited features. We address this critical issue via a new Trigonometric Quadrature Fourier Feature (TQFF) method, which uses a novel non-Gaussian quadrature rule specifically tailored for the desired Fourier transform. We derive an exact quadrature rule for TQFF, along with kernel approximation error bounds for the resulting feature map. We then demonstrate the improved performance of our method over RFF and Gaussian QFF in a suite of numerical experiments and applications, and show the TQFF enjoys accurate GP approximations over a broad range of length-scales using fewer features.


# Summary. An optional shortened abstract.
summary: We develop an Gaussian Process fourier features approximation using a custom quadrature rule targeted at the trignometric form of the kernel function's spectral form. Error analysis shows superior approximation performance relative to Random and Gaussian quadrature fourier feature method. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2310.14544.pdf'
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

---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

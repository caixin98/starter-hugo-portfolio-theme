---
title: 'Gaze estimation with an ensemble of four architectures'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xin Cai
  - Chen, Boyu
  - Zeng, Jiabei 
  - Zhang, Jiajun
  - Sun, Yunjia 
  - Wang, Xiao 
  - Ji, Zhilong 
  - Liu, Xiao
  - Chen, Xilin 
  - Shan, Shiguang


# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-04-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['4']

# Publication name and optional abbreviated publication name.
publication: Report for Winner in ETH-XGaze Challenge CVPR 2021 Gaze WorkShop
publication_short: Report for Winner in ETH-XGaze Challenge *CVPR 2021 Gaze WorkShop*

abstract:  This paper presents a method for gaze estimation according to face images.We train several gaze estimators adopting four different network architectures, including an architecture designed for gaze estimation (i.e.,iTracker-MHSA) and three originally designed for general computer vision tasks(i.e., BoTNet, HRNet,  ResNeSt). Then, we select the best six estimators and ensemble their predictions through a linear combination.The method ranks the first on the leader-board of ETH-XGaze Competition, achieving an average angular error of $3.11^{\circ}$ on the ETH-XGaze test set.

# Summary. An optional shortened abstract.
summary: A method for Gaze Estimation.

tags: [GE,CV]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://github.com/VIPL-TAL-GAZE/GAZE2021'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

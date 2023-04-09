---
title: 'Landmark-aware Self-supervised Eye Semantic Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xin Cai
  - Jiabei Zeng
  - Shiguang Shan

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2021-10-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Automatic Face and Gesture Recognition (FG),2021*
publication_short: In *FG 2021*

abstract:  Learning an accurate and robust eye semantic segmentation model generally requires enormous training data with delicate segmentation annotations.However, labeling the data is time-consuming and manpower-consuming. To address this issue, we propose to segment the eyes using unlabelled eye images and a weak empirical prior on the eye shape. To make the segmentation interpretable, we leverage the prior knowledge of eye shape by converting the self-supervised learned landmarks of each eye component to the segmentation maps.Specifically, we design a symmetrical auto-encoder architecture to learn disentangled representations of eye appearance and eye shape in a self-supervised manner. The eye shape is represented as the landmarks on the eyes.The proposed method encodes the eye images into the eye shapes and appearance features and then it reconstructs the image according to the eye shape and the appearance feature of another image.Since the landmarks of the training images are unknown, we require the generated landmarks' pictorial representations to have the same distribution as a known prior by minimizing an adversarial loss.Experiments on TEyeD and UnitySeg datasets demonstrate that the proposed self-supervised method is comparable with supervised ones. When the labeled data is insufficient, the proposed self-supervised method provides a better pre-trained model than other initialization methods.

# Summary. An optional shortened abstract.
summary: A method for eye semantic segmentation.

tags: [CV]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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

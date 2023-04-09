---
title: 'Source-free Adaptive Gaze Estimation with Uncertainty Reduction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xin Cai
  - Jiabei Zeng
  - Shiguang Shan
  - Xilin Chen

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
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023*
publication_short: In *CVPR 2023*

abstract:  Gaze estimation across domains has been explored recently because the training data are usually collected under controlled conditions while the trained gaze estimators are used in nature and diverse environments. However, due to privacy and efficiency concerns, simultaneous access to annotated source data and to-be-predicted target data can be challenging. In light of this, we present an unsupervised source-free domain adaptation approach for gaze estimation, which adapts a source-trained gaze estimator to unlabeled target domains without source data. We propose the Uncertainty Reduction Gaze Adaptation (UnReGA) framework, which achieves adaptation by reducing both sample and model uncertainty. Sample uncertainty is mitigated by enhancing image quality and making them gaze-estimation-friendly, whereas model uncertainty is reduced by minimizing prediction variance on the same inputs. Extensive experiments are conducted on six cross-domain tasks, demonstrating the effectiveness of UnReGA and its components. Results show that UnReGA outperforms other state-of-the-art cross-domain gaze estimation methods under both protocols, with and without source data. 

# Summary. An optional shortened abstract.
summary: A method for source-free adaptive gaze estimation.

tags: [GE,CV]

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

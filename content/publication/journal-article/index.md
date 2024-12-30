---
title: "Prediction Calibration for Generalized Few-shot Semantic Segmentation"

authors:
- admin
- Robert Ford

# author_notes:
# - "Equal contribution"
# - "Equal contribution"

# Publication name and optional abbreviated publication name.
publication: "TIP"
# publication_short: ""

abstract: Generalized Few-shot Semantic Segmentation (GFSS) aims to segment each image pixel into either base classes with abundant training examples or novel classes with only a handful of (e.g., 1-5) training images per class. Compared to the widely studied Few-shot Semantic Segmentation (FSS), which is limited to segmenting novel classes only, GFSS is much under-studied despite being more practical. Existing approach to GFSS is based on classifier parameter fusion whereby a newly trained novel class classifier and a pre-trained base class classifier are combined to form a new classifier. As the training data is dominated by base classes, this approach is inevitably biased towards the base classes. In this work, we propose a novel Prediction Calibration Network (PCN) to address this problem. Instead of fusing the classifier parameters, we fuse the scores produced separately by the base and novel classifiers. To ensure that the fused scores are not biased to either the base or novel classes, a new Transformer-based calibration module is introduced. It is known that the lower-level features are useful of detecting edge information in an input image than higher-level features. Thus, we build a cross-attention module that guides the classifier’s final prediction using the fused multi-level features. However, transformers are computationally demanding. Crucially, to make the proposed cross-attention module training tractable at the pixel level, this module is designed based on feature-score cross-covariance and episodically trained to be generalizable at inference time. Extensive experiments on PASCAL-5^{i} and COCO-20^{i} show that our PCN outperforms the state-the-the-art alternatives by large margins.

# Summary. An optional shortened abstract.
summary: Investigating the feature-prediction covariance based Transformer for calibrating the biases in GFSS.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10145054
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

title: "Prediction Calibration for Generalized Few-shot Semantic Segmentation"

authors:
- admin
- Robert Ford

# author_notes:
# - "Equal contribution"
# - "Equal contribution"

# Publication name and optional abbreviated publication name.
publication: "TIP"
# publication_short: ""

abstract: Generalized Few-shot Semantic Segmentation (GFSS) aims to segment each image pixel into either base classes with abundant training examples or novel classes with only a handful of (e.g., 1-5) training images per class. Compared to the widely studied Few-shot Semantic Segmentation (FSS), which is limited to segmenting novel classes only, GFSS is much under-studied despite being more practical. Existing approach to GFSS is based on classifier parameter fusion whereby a newly trained novel class classifier and a pre-trained base class classifier are combined to form a new classifier. As the training data is dominated by base classes, this approach is inevitably biased towards the base classes. In this work, we propose a novel Prediction Calibration Network (PCN) to address this problem. Instead of fusing the classifier parameters, we fuse the scores produced separately by the base and novel classifiers. To ensure that the fused scores are not biased to either the base or novel classes, a new Transformer-based calibration module is introduced. It is known that the lower-level features are useful of detecting edge information in an input image than higher-level features. Thus, we build a cross-attention module that guides the classifier’s final prediction using the fused multi-level features. However, transformers are computationally demanding. Crucially, to make the proposed cross-attention module training tractable at the pixel level, this module is designed based on feature-score cross-covariance and episodically trained to be generalizable at inference time. Extensive experiments on PASCAL-5^{i} and COCO-20^{i} show that our PCN outperforms the state-the-the-art alternatives by large margins.

# Summary. An optional shortened abstract.
summary: Investigating the feature-prediction covariance based Transformer for calibrating the biases in GFSS.

tags:
- Source Themes
featured: false

# links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/10145054
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# projects: []
---



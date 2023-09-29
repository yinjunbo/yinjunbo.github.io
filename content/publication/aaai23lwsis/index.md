---
title: 'LWSIS: LiDAR-Guided Weakly Supervised Instance Segmentation for Autonomous Driving'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiang Li
  - Junbo Yin
  - Botian Shi
  - Yikang Li
  - Ruigang Yang
  - Jianbing Shen

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *AAAI 2023*
publication_short: In *AAAI*

abstract: Image instance segmentation is a fundamental research topic in autonomous driving, which is crucial for scene understanding and road safety. Advanced learning-based approaches often rely on the costly 2D mask annotations for training. In this paper, we present a more artful framework, LiDAR-guided Weakly Supervised Instance Segmentation (LWSIS), which leverages the off-the-shelf 3D data, ie, Point Cloud, together with the 3D boxes, as natural weak supervisions for training the 2D image instance segmentation models. Our LWSIS not only exploits the complementary information in multimodal data during training but also significantly reduces the annotation cost of the dense 2D masks. In detail, LWSIS consists of two crucial modules, Point Label Assignment (PLA) and Graph-based Consistency Regularization (GCR). The former module aims to automatically assign the 3D point cloud as 2D point-wise labels, while the atter further refines the predictions by enforcing geometry and appearance consistency of the multimodal data. Moreover, we conduct a secondary instance segmentation annotation on the nuScenes, named nuInsSeg, to encourage further research on multimodal perception tasks. Extensive experiments on the nuInsSeg, as well as the large-scale Waymo, show that LWSIS can substantially improve existing weakly supervised segmentation models by only involving 3D data during training. Additionally, LWSIS can also be incorporated into 3D object detectors like PointPainting to boost the 3D detection performance for free.

# Summary. An optional shortened abstract.
summary: We present a novel learning paradigm, LWSIS, that inherits the fruits of off-the-shelf 3D point cloud to guide the training of 2D instance segmentation models to save mask-level annotations. We advocate a new dataset nuInsSeg based on nuScenes to extend existing 3D LiDAR annotations with 2D image segmentation annotations.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# PDF:
#   'https://openaccess.thecvf.com/content_CVPR_2020/papers/Yin_LiDAR-Based_Online_3D_Video_Object_Detection_With_Graph-Based_Message_Passing_CVPR_2020_paper.pdf'
# cite:
#   'https://github.com/wowchemy/wowchemy-hugo-themes'

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/25228/25000'
url_code: 'https://github. com/Serenos/LWSIS'
url_dataset: 'https://github.com/Serenos/nuInsSeg'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

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
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

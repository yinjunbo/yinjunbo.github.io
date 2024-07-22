---
title: 'IS-FUSION: Instance-Scene Collaborative Fusion for Multimodal 3D Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Junbo Yin
  - Jianbing Shen
  - Runnan Chen
  - Wei Li
  - Ruigang Yan
  - Pascal Frossard
  - Wenguan Wang

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *CVPR 2024*
publication_short: In *CVPR*

abstract: Bird’s eye view (BEV) representation has emerged as a dominant solution for describing 3D space in autonomous driving scenarios. However, objects in the BEV representation typically exhibit small sizes, and the associated point cloud context is inherently sparse, which leads to great challenges for reliable 3D perception. In this paper, we propose IS-F USION, an innovative multimodal fusion framework that jointly captures the Instance- and Scenelevel contextual information. IS-F USION essentially differs from existing approaches that only focus on the BEV scenelevel fusion by explicitly incorporating instance-level multimodal information, thus facilitating the instance-centric tasks like 3D object detection. It comprises a Hierarchical Scene Fusion (HSF) module and an Instance-Guided Fusion (IGF) module. HSF applies Point-to-Grid and Grid-toRegion transformers to capture the multimodal scene context at different granularities. IGF mines instance candidates, explores their relationships, and aggregates the local multimodal context for each instance. These instances then serve as guidance to enhance the scene feature and yield an instance-aware BEV representation. On the challenging nuScenes benchmark, IS-F USION outperforms all the published multimodal works to date.

# Summary. An optional shortened abstract.
summary: A novel multimodal 3D object detection algorithm, IS-Fusion, is presented in this work. It enhances the previous multimodal BEV representation by incorporating instance-level information, which significantly improves detection performance. IS-Fusion achieves the best performance among the published works to date.

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

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2024/papers/Yin_IS-Fusion_Instance-Scene_Collaborative_Fusion_for_Multimodal_3D_Object_Detection_CVPR_2024_paper.pdf'
url_code: 'https://github.com/yinjunbo/IS-Fusion'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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

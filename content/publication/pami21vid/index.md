---
title: "Graph Neural Network and Spatiotempora Transformer Attention for 3D Video Objec Detection From Point Clouds"
authors:
- Junbo Yin
- Jianbing Shen
- Xin Gao
- David J. Crandall 
- Ruigang Yang

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-12-01T00:00:00Z"
doi: "10.1109/TPAMI.2021.3125981"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
publication_short: "TPAMI"

abstract: Previous works for LiDAR-based 3D object detection mainly focus on the single-frame paradigm. In this paper, we propose to detect 3D objects by exploiting temporal information in multiple frames, i.e., the point cloud videos. We empirically categorize the temporal information into short-term and long-term patterns. To encode the short-term data, we present a Grid Message Passing Network (GMPNet), which considers each grid (i.e., the grouped points) as a node and constructs a k-NN graph with the neighbor grids. To update features for a grid, GMPNet iteratively collects information from its neighbors, thus mining the motion cues in grids from nearby frames. To further aggregate the long-term frames, we propose an Attentive Spatiotemporal Transformer GRU (AST-GRU), which contains a Spatial Transformer Attention (STA) module and a Temporal Transformer Attention (TTA) module. STA and TTA enhance the vanilla GRU to focus on small objects and better align the moving objects. Our overall framework supports both online and offline video object detection in point clouds. The evaluation results on the challenging nuScenes benchmark show the superior performance of our method, achieving 1st on the leaderboard without any bells and whistles, by the time the paper is submitted
# Summary. An optional shortened abstract.

summary: A general point cloud-based 3D video object detection framework is proposed by leveraging both short-term and long-term point cloud information. We build the proposed 3D video object detectio framework upon both anchor-based and anchor-fre 3D object detectors. Also, the proposed framework can be easily deployed in both online and offlin modes.

tags: []
# - Source Themes
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9609569'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- # {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
 -->
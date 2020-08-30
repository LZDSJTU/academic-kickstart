---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hierarchical Depthwise Graph Convolutional Neural Network for 3D Semantic Segmentation of Point Clouds"
authors: [Zhidong Liang, Ming Yang, Liuyuan Deng, Chunxiang Wang, Bing Wang]
date: 2019-08-21
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-13T00:06:37+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2019 International Conference on Robotics and Automation (ICRA)"
publication_short: "ICRA 2019"

abstract: "This paper proposes a hierarchical depthwise graph convolutional neural network (HDGCN) for point cloud semantic segmentation. The main chanllenge for learning on point clouds is to capture local structures or relationships. Graph convolution has the strong ability to extract local shape information from neighbors. Inspired by depthwise convolution, we propose a depthwise graph convolution which requires less memory consumption compared with the previous graph convolution. While depthwise graph convolution aggregates features channel-wisely, pointwise convolution is used to learn features across different channels. A customized block called DGConv is specially designed for local feature extraction based on depthwise graph convolution and pointwise convolution. The DGConv block can extract features from points and transfer features to neighbors while being invariant to different point orders. HDGCN is constructed by a series of DGConv blocks using a hierarchical structure which can extract both local and global features of point clouds. Experiments show that HDGCN achieves the state-of-the-art performance in the indoor dataset S3DIS and the outdoor dataset Paris-Lille-3D."

# Summary. An optional shortened abstract.
summary: "2019 International Conference on Robotics and Automation (ICRA 2019)"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/8794052/
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
slides: ""
---

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "3D Instance Embedding Learning With a Structure Aware Loss Function for Point Cloud Segmentation"
authors: [Zhidong Liang, Ming Yang, Hao Li, Chunxiang Wang]
date: 2020-06-25
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-14T23:51:29+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters with joint IROS 2020 option"
publication_short: "RA-L (IROS 2020)"

abstract: "This letter presents a framework for 3D instance segmentation on point clouds. A 3D convolutional neural network is used as the backbone to generate semantic predictions and instance embeddings simultaneously. In addition to the embedding information, point clouds also provide 3D geometric information which reflects the relation between points. Considering both types of information, the structure-aware loss function is proposed to achieve discriminative embeddings for each 3D instance. To eliminate the quantization error caused by 3D voxel, the attention-based k-nearest neighbor (kNN) is proposed. Different from the average strategy, it learns different weights for different neighbors to aggregate and update the instance embeddings. Our network can be trained in an end-to-end style. Experiments show that our approach achieves state-of-the-art performance on two challenging datasets for instance segmentation."

# Summary. An optional shortened abstract.
summary: "IEEE Robotics and Automation Letters (also presented in IROS 2020)"

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

url_pdf: https://ieeexplore.ieee.org/abstract/document/9126193
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

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Context-Aware Group Captioning via Self-Attention and Contrastive Features"
summary: ""
authors: ["**Zhuowan Li**", "Quan Tran", "Long Mai", "Zhe Lin", "Alan Yuille"]
tags: []
categories: []
date: 2020-03-23T18:22:34-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
{{< figure src="featured.jpg" title=
"<p style='text-align: justify;'> Context-ware group captioning. Given a group of target images (shown in orange boxes) and a group of reference images which provide the context (<b>woman</b>), the goal is to generatea language description (<b>woman with cowboy hat</b>) that best describes the target group while taking into account the context depicted by the reference group. </p>"
 lightbox="true" >}}

## Abstract
While image captioning has progressed rapidly, existing works focus mainly on describing single images. In this paper, we introduce a new task, context-aware group captioning, which aims to describe a group of target images in the context of another group of related reference images. Context-aware group captioning requires not only summarizing information from both the target and reference image group but also contrasting between them. To solve this problem, we propose a framework combining self-attention mechanism with contrastive feature construction to effectively summarize common information from each image group while capturing discriminative information between them. To build the dataset for this task, we propose to group the images and generate the group captions based on single image captions using scene graphs matching. Our datasets are constructed on top of the public Conceptual Captions dataset and our new Stock Captions dataset. Experiments on the two datasets show the effectiveness of our method on this new task.

## Datasets
{{< figure src="dataset.png" title="Table: Statistics of Conceptual Captions and Stock Captions" lightbox="true" >}}
 - Conceptual Captions Dataset
   - Coming up soon.
 - Stock Captions Dataset
   - Coming up soon.

## Code
Code in Pytorch coming up soon

---
title: "A digital twin approach for weld penetration prediction of tig welding with dual ellipsoid heat source"
authors:
- Huangyi Qu
- admin
- Yi Cai

author_notes:
- 
-
- Corresponding author
date: "2024-06-24T00:00:00Z"
doi: "https://doi.org/10.1007/s10845-024-02431-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "* Journal of Intelligent Manufacturing, 1*(1)"
publication_short: ""

abstract:Tungsten Inert Gas (TIG) welding is a manufacturing process that utilizes argon as a shielding gas and tungsten as an electrode to join metals at high temperatures. The weld penetration is the key to determine the quality of the weld. However, the lack of sensing technology makes weld penetration difficult to predict, which imposes a major challenge to process stability and weld quality. To address this challenge, a digital twin-driven method is proposed for characterizing the melt pool morphology and melt penetration prediction. To achieve this, an analytical model of the melt pool with time-varying welding speed under the action of a double ellipsoidal circular heat source is first derived. The analytical model is solved using the numerical integration method. The prediction of melt depth and melt width is achieved by extracting isotherms. Meanwhile, a digital reconstruction of the welding scene was achieved by implementing the Neural Radiance Fields (NeRF) method. The target rendering of the melt pool and welding scene is accomplished by constructing voxels and meshes. Furthermore, VR is utilized as the interface for human–computer interaction, and a digital twin model of the molten pool morphology and welding scene is generated. The prediction model's accuracy is verified through welding experiments using 304L steel on a robotic welding system. The results show that in the 0–4 s stage, the penetration error is controlled within 7%. In the stage of 4–16 s when the speed changes, the maximum error of penetration is 16.59%. In terms of welding scene reconstruction quality, PSNR is 33.98 and SSIM reaches 0.9032. The method allows real-life simulation of different welding conditions and parameter combinations prior to welding, assessing their impact on the welding results, in order to find the optimal configuration of process parameters. It can also be remotely realized to monitor and control the melt penetration in real-time during the welding process. This method provides a new solution and a theoretical guidance system to solve the welding penetration control problems and it plays an important role in promoting welding intelligence.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://link.springer.com/article/10.1007/s10845-024-02431-1'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

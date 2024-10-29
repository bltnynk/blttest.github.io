---
title: "Enhancing Fractional Gradient Descent with Learned Optimizers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
    - admin
    - Petr Šimánek
    - Pavel Kordík

# Author notes (optional)
# author_notes:
#   - "First author"
#   - "Equal contribution"
#   - "Equal contribution"

date: "2024-09-01T00:00:00Z"
# doi: "10.5220/0012317000003636"

# Schedule page publish date (NOT publication"s date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Submitted"]

# Publication name and optional abbreviated publication name.
publication: "Optimization Letters (Springer)"
# publication_short: ""

abstract: Fractional Gradient Descent (FGD) offers a novel and promising way to accelerate optimization by incorporating fractional calculus into machine learning. Although FGD has shown encouraging initial results across various optimization tasks, it faces significant challenges with convergence behavior and hyperparameter selection. Moreover, the impact of its hyperparameters is not fully understood, and scheduling them is particularly difficult in non-convex settings such as neural network training. To address these issues, we propose a novel approach called Learning to Optimize Caputo Fractional Gradient Descent (L2O-CFGD), which meta-learns how to dynamically tune the hyperparameters of Caputo FGD (CFGD). Our method's meta-learned schedule outperforms CFGD with static hyperparameters found through an extensive search and, in some tasks, achieves performance comparable to a fully black-box meta-learned optimizer. L2O-CFGD can thus serve as a powerful tool for researchers to identify high-performing hyperparameters and gain insights on how to leverage the history-dependence of the fractional differential in optimization.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: false

# # Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: "https://dspace.cvut.cz/bitstream/handle/10467/115880/F8-BP-2024-Sobotka-Jan-thesis.pdf?sequence=-1&isAllowed=y"
# url_code: "https://github.com/HugoBlox/hugo-blox-builder"
# url_dataset: "https://github.com/HugoBlox/hugo-blox-builder"
# url_poster: ""
# url_project: ""
# url_slides: ""
# url_source: "https://github.com/HugoBlox/hugo-blox-builder"
# url_video: "https://youtube.com"

# Featured image
# To use, add an image named `featured.jpg/png` to your page"s folder.
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project"s folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck"s filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---




<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication"s **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

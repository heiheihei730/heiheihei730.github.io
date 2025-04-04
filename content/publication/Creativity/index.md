---
title: "Probing the “Creativity” of Large Language Models: Can models produce divergent semantic association?"
authors:
- Honghua Chen
- Nai Ding
date: "2023-12-08T00:00:00Z"
doi: "10.18653/v1/2023.findings-emnlp.858"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Conference paper"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 

# Summary. An optional shortened abstract.
summary: A comparison of creativity of LLMs

tags:
- NLP

featured: true

links:
url_pdf: https://aclanthology.org/2023.findings-emnlp.858.pdf
url_code: 'https://github.com/DingNLab/probing_creativity'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
Large language models possess remarkable capacity for processing language, but it remains unclear whether these models can further generate creative content. The present study aims to investigate the creative thinking of large language models through a cognitive perspective. We utilize the divergent association task (DAT), an objective measurement of creativity that asks models to generate unrelated words and calculates the semantic distance between them. We compare the results across different models and decoding strategies. Our findings indicate that (1) When using the greedy search strategy, GPT-4 outperforms 96% of humans, while GPT-3.5-turbo exceeds the average human level. (2) Stochastic sampling and temperature scaling are effective to obtain higher DAT scores for models except GPT-4, but face a trade-off between creativity and stability. These results imply that advanced large language models have divergent semantic associations, which is a fundamental process underlying creativity.


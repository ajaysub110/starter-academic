---
title: "Benchmarking dynamic neural-network models of the human speed-accuracy tradeoff"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Elena Sizikova
- Omkar Kumbhar
- Najib Majaj
- Denis G. Pelli

# Author notes (optional)
# author_notes:

date: "2022-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Poster at *Vision Science Society (VSS) Meeting*
# publication_short: In *ArXiv*

abstract: People take a variable amount of time (0.1 - 10 s) to recognize an object and can trade speed for accuracy. Various time-constrained tasks demand a wide range of accuracy and latency. Previous work (Spoerer’20) has modeled only modest speed-accuracy tradeoffs (SATs) with a min-to-max range of merely 6% accuracy and 200 ms reaction time, a tiny fraction of the human range. Here, we collect and present a public human benchmark where we use image perturbations to adjust task difficulty and increase the accuracy range to more than 50%. Furthermore, we show that dynamic neural networks are a promising model of the SAT and capture the behavior without needing recurrence. 142 online participants categorized CIFAR-10 images with controlled reaction time. Reaction time (RT) was defined as the elapsed time between stimulus presentation and a keypress response. We ran 5 blocks of 300 trials, each with a different reaction time from 200-1000 ms and repeated the experiment with 4 different viewing conditions, color, grayscale, noise, and blur. Three networks, MSDNet (Huang’17), SCAN (Zhang’19), and ConvRNN (Spoerer’20) were trained on CIFAR-10 image classification. Using FLOPs as an analogue for human reaction time, we tested these networks by forcing them to “respond” using different amounts of computation, across all viewing conditions. We compared the three networks and humans using two metrics, accuracy range (difference between maximum and minimum accuracy when reaction time is varied) and correlation between speed-accuracy trade-off curves. MSDNet gives a better account than previous attempts without needing recurrence. When trained with noise, it shows high correlation (0.93) with human SAT. However, humans are much more flexible, with a large 51% accuracy range while the best network, MSDNet trained with noise, shows only 19%. Thus, our benchmark presents a challenging goal for future work that aims to model SAT.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
#   caption: ''
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
slides: ""
---

---
title: "SATBench: A Benchmark of the Human Speed-Accuracy Tradeoff in Recognizing Objects"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Omkar Kumbhar
- Elena Sizikova
- Najib Majaj
- Denis G. Pelli

# Author notes (optional)
# author_notes:

date: "2021-08-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Pre-print
# publication_short: In *ArXiv*

abstract: People take a variable amount of time, 0.1 to 10 s, to recognize an object. The reaction time depends on the stimulus and task, and people can trade off speed for accuracy. That tradeoff is a crucial human skill. Neural networks exhibit high accuracy in object recognition, but most current models cannot dynamically adapt to respond with less computation, which is a problem in time-sensitive applications like driving. Towards the goal of using networks to model how people recognize objects, we here present a benchmark dataset (with model fits) of the human speed-accuracy tradeoff (SAT) in recognizing CIFAR-10 and STL-10 images. In each trial, a beep, indicating the desired reaction time, sounds at a fixed delay after the target onset, and the observer's response counts only if it occurs near the time of the beep. With practice, observers quickly learn to respond at the time of the beep. In a series of blocks, we test many beep latencies, i.e., reaction times. We observe that human accuracy increases with reaction time, and we compare its characteristics with the behavior of several dynamic neural networks that can trade off speed and accuracy. After limiting the network resources and adding image perturbations (grayscale conversion, noise, blur) to bring the two observers (human and network) into the same accuracy range, we show that humans and networks exhibit very similar tradeoffs. We conclude that dynamic neural networks are a promising model of human reaction time in recognition tasks. Our dataset and code are publicly available.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [visual object recognition, computer vision, psychophysics, psychology]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=gZKTMm2Dt5'
url_code: 'https://github.com/ajaysub110/anytime-prediction'
url_dataset: 'https://osf.io/zkvep/'
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

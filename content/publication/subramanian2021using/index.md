---
title: "Using Dynamic Neural Networks to Model the Speed-Accuracy Trade-Off in People"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Omkar Kumbhar
- Elena Sizikova
- Najib Majaj
- Denis Pelli

# Author notes (optional)
# author_notes:

date: "2021-06-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Under Review at *NeurIPS 2021 Datasets and Benchmarks Track*
# publication_short: In *ArXiv*

abstract: Neural networks have been shown to exhibit remarkable object recognition performance. We ask here whether such networks can provide a useful model for how people recognize objects. Human recognition time varies, from 0.1 to 10 s, depending on the stimulus and task. Slowness of recognition is a key feature in some public health issues, such as dyslexia, so it is crucial to create a model of human speed-accuracy trade-offs. This is an essential aspect of any useful computational model of human cognitive behavior. We present a benchmark dataset for human speed-accuracy trade-off in recognizing a CIFAR-10 image~\cite{Krizhevsky09learningmultiple} from a set of provided class labels. Within a series of trials, a beep sounds at a fixed delay after the target (the desired reaction time), and the response counts only if it occurs near that time. We observe that accuracy grows with reaction time and examine several dynamic neural networks that exhibit a speed-accuracy trade-off as humans do. After limiting the network resources and adding image perturbations (grayscale conversion, noise, blur) to bring the two observers (human and network) into the same accuracy range, humans and networks show very similar dependence on duration or floating point operations (FLOPS). We conclude that dynamic neural networks are a promising model of human reaction time in recognition tasks. Understanding how the brain allocates appropriate resources under time pressure would be a milestone in neuroscience and a first step toward understanding conditions like dyslexia. Our dataset and code are publicly available.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [visual object recognition, computer vision, psychophysics, psychology]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=pOf_IV_-XG'
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

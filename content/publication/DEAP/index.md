+++
title = "DEAP Cache: Deep Eviction Admission and Prefetching for Cache"
date = 2020-09-19T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ayush Mangal*", "Jitesh Jain*", "Keerat Kaur Gullani*", "Omkar Bhalero*"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Working paper
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Under Review"
publication_short = "Under Review"

# Abstract and optional shortened version.
abstract = "Recent approaches for learning policies to improve caching, target just one out of the prefetching, admission and eviction processes. In contrast, we propose an end to end pipeline to learn all three policies using machine learning. We also take inspiration from the success of pretraining on large corpora to learn specialized embeddings for the task. We model prefetching as a sequence prediction task based on past misses. Following previous works suggesting that frequency and recency are the two orthogonal fundamental attributes for caching, we use an online reinforcement learning technique to learn the optimal policy distribution between two orthogonal eviction strategies based on them. While previous approaches used the past as an indicator of the future, we instead explicitly model the future frequency and recency in a multitask fashion with prefetching, leveraging the abilities of deep networks to capture futuristic trends and use them for learning eviction and admission. We also model the distribution of the data in an online fashion using Kernel Density Estimation in our approach, to deal with the problem of caching non-stationary data. We present our approach as a ”proof of concept” of learning all three components of cache strategies using machine learning and leave improving practical deployment for future work."

abstract_short = "Recent approaches for learning policies to improve caching, target just one out of the prefetching, admission and eviction processes. In contrast, we propose an end to end pipeline to learn all three policies using machine learning"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning.md"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/2009.09206"
url_code = "https://github.com/vlgiitr/deep_cache_replacement"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# [header]
# image = "cache.png"
# caption = "DEAP Cache: Deep Eviction Admission and Prefetching for Cache"

+++

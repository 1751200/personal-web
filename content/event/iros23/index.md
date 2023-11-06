---
title: Example Talk

event: IROS 2023 Regular Session - Planning for Distributed and Multi-Robot Systems II
event_url: https://example.org

location: Huntington Place
address:
  street: 1 Washington Boulevard
  city: Detroit
  region: MI
  postcode: '48226'
  country: United States

summary: An oral presentation of our accepted paper ``HELSA Hierarchical Reinforcement Learning with Spatiotemporal Abstraction for Large-Scale Multi-Agent Path Finding''.
abstract: The Multi-Agent Path Finding (MAPF) problem is a critical challenge in dynamic multi-robot systems. Recent studies have revealed that multi-agent reinforcement learning (MARL) is a promising approach to solving MAPF problems in a fully decentralized manner. However, as the size of the multirobot system increases, sample inefﬁciency becomes a major impediment to learning-based methods. This paper presents a hierarchical reinforcement learning (HRL) framework for large-scale multi-agent path ﬁnding, featuring applying spatial and temporal abstraction to capture intermediate reward and thus encourage efﬁcient exploration. Speciﬁcally, we introduce a meta controller that partitions the map into interconnected regions and optimizes agents’ region-wise paths towards globally better solutions. Additionally, we design a lower-level controller that efﬁciently solves each sub-problem by incorporating heuristic guidance and an inter-agent communication mechanism with RL-based policies. Our empirical results on test instances of various scales demonstrate that our method outperforms existing approaches in terms of both success rate and makespan.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-10-03T14:24:00Z'
date_end: '2023-10-03T14:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: [Zhaoyi Song]
tags: [IROS 2023]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ieeeiros
#url_code: ''
url_pdf: 'iros2023.pdf'
url_slides: 'IROS23_Slides.pdf'
#url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "iros23-slides"` references `content/slides/iros23-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.

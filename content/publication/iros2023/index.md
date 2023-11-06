---
title: 'HELSA: Hierarchical Reinforcement Learning with Spatiotemporal Abstraction for Large-Scale Multi-Agent Path Finding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rongqing Zhang *
  - Xiang Cheng

# Author notes (optional)
author_notes:
  - 'First Author'
  - 'Corresponding Author'
  - ''

date: '2023-10-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2023)*
publication_short: In *IROS 2023*

abstract: The Multi-Agent Path Finding (MAPF) problem is a critical challenge in dynamic multi-robot systems. Recent studies have revealed that multi-agent reinforcement learning (MARL) is a promising approach to solving MAPF problems in a fully decentralized manner. However, as the size of the multirobot system increases, sample inefﬁciency becomes a major impediment to learning-based methods. This paper presents a hierarchical reinforcement learning (HRL) framework for large-scale multi-agent path ﬁnding, featuring applying spatial and temporal abstraction to capture intermediate reward and thus encourage efﬁcient exploration. Speciﬁcally, we introduce a meta controller that partitions the map into interconnected regions and optimizes agents’ region-wise paths towards globally better solutions. Additionally, we design a lower-level controller that efﬁciently solves each sub-problem by incorporating heuristic guidance and an inter-agent communication mechanism with RL-based policies. Our empirical results on test instances of various scales demonstrate that our method outperforms existing approaches in terms of both success rate and makespan.

# Summary. An optional shortened abstract.
summary: Proposed a hierarchical reinforcement learning framework for large-scale multi-agent pathfinding, addressing the challenges of sample inefficiency resulting from sparse rewards and partial observability.

tags: [IROS, Robotics, Reinforcement Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'IROS 2023 Poster'
  focal_point: ''
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

[//]: # ({{% callout note %}})

[//]: # (Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.)

[//]: # ({{% /callout %}})

[//]: # ()
[//]: # ({{% callout note %}})

[//]: # (Create your slides in Markdown - click the _Slides_ button to check out the example.)

[//]: # ({{% /callout %}})

[//]: # ()
[//]: # (Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images]&#40;https://wowchemy.com/docs/content/writing-markdown-latex/&#41;.)

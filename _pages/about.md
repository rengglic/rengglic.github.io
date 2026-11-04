---
layout: about
title: About
permalink: /
subtitle:

profile:
  align: right
  image: cedric_renggli.jpg
  image_circular: true # crops the image to make it circular
  more_info:

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: false # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Senior Researcher and Lecturer at [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch), working with [Ana Klimovic](https://anakli.inf.ethz.ch).

I do research at the intersection of data management and AI systems. My goal is to make AI systems efficient and reliable, so that users reach validated results with less computation, data, and expert effort.

Previously, I was a Senior Researcher at [Apple](https://www.apple.com) and a PostDoc at UZH ([DaST](https://www.ifi.uzh.ch/en/dast.html), with [Dan Olteanu](https://www.ifi.uzh.ch/en/dast/people/Olteanu.html)). I received my PhD from [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch), advised by [Ce Zhang](https://zhangce.github.io).

<!-- **If you are interested in collaborating, please reach out directly. I also welcome motivated students at ETH for projects and theses. To apply, send me an email with your CV and transcript of records attached.** -->

<h2 class="mb-3">Research</h2>

With talented students and collaborators, I work on two broad areas.

With talented students and collaborators, I work on two broad areas.

<div class="research-area" markdown="1"> <h3>Efficiency</h3>

I currently lead projects on efficient AI serving and post-training, together with CSCS and the Swiss AI Initiative. My work uses signals from models, tools, and user interactions to route requests to the cheapest capable model, decide which KV-cache state to keep or evict, and stop agent trajectories that are unlikely to succeed. For reinforcement-learning post-training, I study how to schedule and isolate sandboxes so that GPU and CPU work overlap.

Earlier work includes SparCML, sparse communication for distributed training (SC'19); SHiFT, a search engine for pretrained models (VLDB'22); CorgiPile, in-database training without a full data shuffle (VLDB Journal'24); and Ada-IVF, incremental index maintenance for streaming vector search.

</div> <div class="research-area" markdown="1"> <h3>Reliability</h3>

I study what limits the quality of AI and how to verify that it works. Much of this work is data-centric. Snoopy estimates the best achievable accuracy for a task from the data alone, before any model is trained (ICDE'23), building on FeeBee, a framework for evaluating Bayes error estimators (NeurIPS'21). ease.ml/ci provides continuous integration for ML models with statistical guarantees (SysML'19). My work on Text2SQL evaluation separates the limitations of a solution from those of the evaluation data and metrics (2025).

Quality issues also arise beyond the data. In agentic workloads, environment friction such as flaky tests, missing dependencies, and timeouts is easily mistaken for model failure and corrupts reward signals during post-training. I currently study how to detect and separate these effects, so that every efficiency gain comes with a statement of what it may cost in correctness.

</div>

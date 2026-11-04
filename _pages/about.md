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

**I work at the intersection of data management and AI systems.**

Data challenges arise at every layer of modern AI. Models are trained on large, continuously evolving datasets. At inference time, they retrieve information from vector indexes and databases and accumulate state such as KV caches. Their quality is assessed with benchmarks, which are themselves datasets. We bring core principles of data management (indexing, caching, incremental maintenance, query optimization, and statistical rigor) to the systems that train, serve, and evaluate AI.

Previously, I was a Senior Researcher at [Apple](https://www.apple.com) and a PostDoc at UZH ([DaST](https://www.ifi.uzh.ch/en/dast.html), with [Dan Olteanu](https://www.ifi.uzh.ch/en/dast/people/Olteanu.html)). I received my PhD from [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch), advised by [Ce Zhang](https://zhangce.github.io).

<!-- **If you are interested in collaborating, please reach out directly. I also welcome motivated students at ETH for projects and theses. To apply, send me an email with your CV and transcript of records attached.** -->

<h2 class="mb-3">Research</h2>

Our research spans two areas, corresponding to the two sides of this intersection.

<div class="research-area" markdown="1">
<h3>1. Data management for AI</h3>
<p class="research-question">How can we organize, search, and assess the data that AI systems are built on and evaluated with?</p>

We build systems that manage the data AI depends on. Examples include [SHiFT](https://www.vldb.org/pvldb/vol16/p304-renggli.pdf), a search engine over large repositories of pretrained models (VLDB'22); [CorgiPile](https://dl.acm.org/doi/abs/10.1007/s00778-024-00845-0), which enables efficient in-database training without a full data shuffle (VLDB Journal'24); and [Ada-IVF](https://arxiv.org/pdf/2411.00970), which maintains vector-search indexes under streaming updates, complemented by [hardware–algorithm co-design for vector search](https://dl.acm.org/doi/abs/10.1145/3581784.3607045) (SC'23).

The same perspective applies to evaluation, since benchmarks are data as well. Observed performance reflects not only model capability, but also data quality, benchmark construction, and random variation. We develop methods to disentangle these factors: estimating from the data alone whether a target accuracy is attainable ([Snoopy](https://ieeexplore.ieee.org/abstract/document/10184817), ICDE'23), statistically rigorous testing of ML models ([ease.ml/ci](https://proceedings.mlsys.org/paper_files/paper/2019/file/4284d31e68c0a4a39dcdad167ac4bd72-Paper.pdf), SysML'19), and identifying ambiguities and metric biases in [Text-to-SQL benchmarks](https://arxiv.org/pdf/2501.18197) (2025).
</div>

<div class="research-area" markdown="1">
<h3>2. Systems for large-scale AI</h3>
<p class="research-question">How can we train and serve large models efficiently?</p>

Our earlier work reduced communication costs in distributed training ([SparCML](https://dl.acm.org/doi/abs/10.1145/3295500.3356222), SC'19) and made training robust to unreliable networks ([ICML'19](https://proceedings.mlr.press/v97/yu19f/yu19f.pdf)). Our current focus is LLM inference and agentic workloads, which accumulate state over many steps, including KV caches, retrieved context, and tool outputs. We treat this state as data that must be cached, placed, and scheduled efficiently across GPUs and machines.
</div>

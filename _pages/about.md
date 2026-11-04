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

I do research at the intersection of AI systems and data management. My goal is to make AI systems efficient and reliable, so that users reach validated results with less data, computation, and expert effort.

Previously, I was a Senior Researcher at [Apple](https://www.apple.com) and a PostDoc at UZH ([DaST](https://www.ifi.uzh.ch/en/dast.html), with [Dan Olteanu](https://www.ifi.uzh.ch/en/dast/people/Olteanu.html)). I received my PhD from [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch), advised by [Ce Zhang](https://zhangce.github.io).

<!-- **If you are interested in collaborating, please reach out directly. I also welcome motivated students at ETH for projects and theses. To apply, send me an email with your CV and transcript of records attached.** -->

<h2 class="mb-3">Research</h2>

With talented students and collaborators, I work on two broad areas around AI systems.

<div class="research-area" markdown="1">
<h3>Efficiency</h3>
I make AI cheaper to develop, train, and serve. On the systems side, this ranges from communication-efficient distributed training ([SparCML](https://dl.acm.org/doi/abs/10.1145/3295500.3356222), SC'19) to my current work on efficient serving and post-training of agentic AI, together with [CSCS](https://www.cscs.ch) and the [Swiss AI Initiative](https://www.swiss-ai.org). On the data side, I reduce the samples, labels, and data movement needed to reach a result, for example when testing models ([ease.ml/ci](https://proceedings.mlsys.org/paper_files/paper/2019/file/4284d31e68c0a4a39dcdad167ac4bd72-Paper.pdf), SysML'19), selecting pretrained models ([SHiFT](https://www.vldb.org/pvldb/vol16/p304-renggli.pdf), VLDB'22), training inside databases ([CorgiPile](https://dl.acm.org/doi/abs/10.1007/s00778-024-00845-0), VLDB Journal'24), or maintaining vector indexes ([Ada-IVF](https://arxiv.org/pdf/2411.00970)).
</div>

<div class="research-area" markdown="1">
<h3>Reliability</h3>
I study what limits the quality of AI and how to verify that it works. On the data side, this includes estimating the best achievable accuracy from the data alone ([Snoopy](https://ieeexplore.ieee.org/abstract/document/10184817), ICDE'23; [FeeBee](https://arxiv.org/abs/2108.13034), NeurIPS'21), statistical guarantees for model testing (ease.ml/ci), and separating solution, data, and metric limitations in [Text2SQL evaluation](https://arxiv.org/pdf/2501.18197) (2025). On the systems side, I study quality issues that arise from execution environments and from efficiency optimizations themselves, particularly in agentic workloads.
</div>

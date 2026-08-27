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

I am a Senior Researcher and Lecturer at [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch) working with [Ana Klimovic](https://anakli.inf.ethz.ch).

<!-- My intro slides summarizing the fast-moving space are available [here](https://docs.google.com/presentation/d/1DUjptGUfT6A__kuNDKbKLh1Yk3v8R0vUxCL4FiXd7lk/edit?usp=sharing). -->

My research lies at the intersection of data management and AI systems. I research and build systems that make emerging AI workloads efficient, adaptive, and measurable. My work addresses three connected questions: How should AI systems manage the data and knowledge they consume and produce? How can stateful AI workloads be executed efficiently? And how can their behavior be measured reliably from noisy observations?

Previously, I was a Senior Researcher at [Apple](https://www.apple.com), a PostDoc at UZH ([DaST](https://www.ifi.uzh.ch/en/dast.html) with [Dan Olteanu](https://www.ifi.uzh.ch/en/dast/people/Olteanu.html)) and defended my thesis at [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch) with [Ce Zhang](https://zhangce.github.io).

**If you are interested in collaborating, please reach out directly. I also welcome motivated students at ETH for projects and theses. To apply, send me an email with your CV and transcript of records attached.**

<h2 class="mb-4">Research Focus Areas</h2>

<div class="accordion research-accordion" id="researchFocusAccordion">
  <div class="card">
    <div class="card-header" id="headingFocus1">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus1" aria-expanded="false" aria-controls="collapseFocus1">
          A. Data Systems for AI
        </button>
      </h5>
    </div>
    <div id="collapseFocus1" class="collapse" aria-labelledby="headingFocus1" data-parent="#researchFocusAccordion">
      <div class="card-body">
        {{ "I develop data systems for efficiently organizing, maintaining, and querying the data used by AI applications. My previous work includes scalable search over pretrained models in [SHiFT](https://www.vldb.org/pvldb/vol16/p304-renggli.pdf), efficient in-database learning without full data shuffling in [CorgiPile](https://dl.acm.org/doi/abs/10.1007/s00778-024-00845-0), and incremental maintenance of vector-search indexes in [Ada-IVF](https://arxiv.org/pdf/2411.00970). Building on these foundations, I am interested in systems that automatically transform evolving data, model outputs, and interaction traces into maintainable and queryable knowledge, with statistical guarantees on answer quality and uncertainty." | markdownify }}
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFocus2">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus2" aria-expanded="false" aria-controls="collapseFocus2">
          B. Efficient and Adaptive AI Systems
        </button>
      </h5>
    </div>
    <div id="collapseFocus2" class="collapse" aria-labelledby="headingFocus2" data-parent="#researchFocusAccordion">
      <div class="card-body">
        {{ "Emerging AI workloads are increasingly stateful and interactive, comprising sequences of model calls, retrieval operations, tool executions, and user interventions whose resource demands evolve over time. I design serving architectures, state-management mechanisms, and adaptive scheduling policies for these workloads. This agenda extends my earlier work on communication-efficient distributed learning in [SparCML](https://dl.acm.org/doi/abs/10.1145/3295500.3356222) and robust execution across unreliable infrastructure in [Distributed Learning over Unreliable Networks](https://proceedings.mlr.press/v97/yu19f/yu19f.pdf). My current interests include managing intermediate execution state (e.g., KV caches), predicting future resource requirements from interaction traces, and coordinating model inference and secure tool execution across heterogeneous hardware." | markdownify }}
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFocus3">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus3" aria-expanded="false" aria-controls="collapseFocus3">
          C. Data Quality and Evaluation
        </button>
      </h5>
    </div>
    <div id="collapseFocus3" class="collapse" aria-labelledby="headingFocus3" data-parent="#researchFocusAccordion">
      <div class="card-body">
        {{ "The observed performance of an AI system reflects not only model capability, but also [data quality](https://rengglic.github.io/assets/pdf/ieee-tcde-mlops.pdf), benchmark construction, infrastructure, execution environments, and stochastic variation. I develop methods for identifying and quantifying these effects. My work has exposed systematic ambiguities and metric biases in [Text-to-SQL evaluation](https://arxiv.org/pdf/2501.18197), introduced automatic feasibility assessment through data-quality analysis in [Snoopy](https://ieeexplore.ieee.org/abstract/document/10184817), and established statistically rigorous testing methods for ML pipelines in [ease.ml/ci](https://proceedings.mlsys.org/paper_files/paper/2019/file/4284d31e68c0a4a39dcdad167ac4bd72-Paper.pdf). By disentangling model behavior from data, system, and measurement artifacts, this research enables more reliable comparisons and better-informed decisions about complete AI systems." | markdownify }}
      </div>
    </div>
  </div>
</div>

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

I am a Senior Researcher and Lecturer at [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch) working with [Ana Klimovic](https://anakli.inf.ethz.ch). I am co-teaching a seminar on [Systems for AI](https://systems.ethz.ch/education/courses/2025-autumn-semester/systems-for-ai-seminar.html).

<!-- My intro slides summarizing the fast-moving space are available [here](https://docs.google.com/presentation/d/1DUjptGUfT6A__kuNDKbKLh1Yk3v8R0vUxCL4FiXd7lk/edit?usp=sharing). -->

My research is centered around efficient AI and data systems, focusing on how large-scale AI workloads can be served reliably and efficiently under real-world constraints. My work emphasizes principled abstractions, declarative system design, and the identification of fundamental trade-offs that shape scalable, trustworthy AI infrastructure.

Previously, I was a Senior Researcher at [Apple](https://www.apple.com), a PostDoc at UZH ([DaST](https://www.ifi.uzh.ch/en/dast.html) with [Dan Olteanu](https://www.ifi.uzh.ch/en/dast/people/Olteanu.html)) and defended my thesis at [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch) with [Ce Zhang](https://zhangce.github.io).

**If you are interested in collaborating, please reach out directly. I also welcome motivated students at ETH for projects and theses. To apply, send me an email with your CV and transcript of records attached.**

<h2 class="mb-4">Research Focus Areas</h2>

<div class="accordion research-accordion" id="researchFocusAccordion">
  <div class="card">
    <div class="card-header" id="headingFocus1">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus1" aria-expanded="false" aria-controls="collapseFocus1">
          I. Systems for Efficient AI Inference and State Management
        </button>
      </h5>
    </div>
    <div id="collapseFocus1" class="collapse" aria-labelledby="headingFocus1" data-parent="#researchFocusAccordion">
      <div class="card-body">
        As large‑scale machine‑learning models become central to modern applications, the underlying systems must efficiently manage computation and intermediate state under tight latency and resource constraints. Our research focuses on the systems challenges of serving complex, sequential AI workloads, such as large language models and reinforcement‑learning pipelines, including secure sandboxed executions. We design distributed infrastructure and scheduling mechanisms that optimize the memory hierarchy and intermediate state (e.g., key‑value caching) while accounting for secure tool execution across heterogeneous hardware. By bridging the gap between model architectures and physical hardware constraints, we aim to improve the throughput, reliability, and cost‑efficiency of AI serving systems in production environments. 
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFocus2">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus2" aria-expanded="false" aria-controls="collapseFocus2">
          II. Modeling and Predicting Interactive System Behavior
        </button>
      </h5>
    </div>
    <div id="collapseFocus2" class="collapse" aria-labelledby="headingFocus2" data-parent="#researchFocusAccordion">
      <div class="card-body">
        Modern AI systems increasingly operate dynamically, adapting their behavior based on continuous user interactions and tool utilization. Understanding how these systems perform in real‑world settings requires moving beyond static benchmarks and analyzing the execution traces generated during deployment. We investigate methods to model and predict the outcomes of these interactive workloads—such as anticipating resource requirements or determining optimal model‑switching strategies in real‑time serving engines. By developing systems that can learn from and act upon execution traces, we aim to improve the adaptability, reliability, and overall performance of interactive AI applications. 
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFocus3">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus3" aria-expanded="false" aria-controls="collapseFocus3">
          III. Trustworthy Evaluation and Noise Characterization for AI Systems
        </button>
      </h5>
    </div>
    <div id="collapseFocus3" class="collapse" aria-labelledby="headingFocus3" data-parent="#researchFocusAccordion">
      <div class="card-body">
        The reliability of AI systems heavily depends on our ability to accurately evaluate their performance, which is often obscured by noise from various sources in the deployment pipeline. Our research addresses the fundamental challenge of isolating true model behavior from artifacts introduced by infrastructure, evaluation sandboxes, biased metrics, and low‑quality data. We build tools and methodologies for automatic feasibility assessment, data‑quality analysis, and noise disentanglement to better understand the fundamental limits and actual system performance. By providing a more precise picture of system behavior under real‑world conditions, we enable practitioners to build more trustworthy and robust AI pipelines.
      </div>
    </div>
  </div>
</div>

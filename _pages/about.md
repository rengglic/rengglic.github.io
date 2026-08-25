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

My research lies at the intersection of AI systems and data management. I design efficient and reliable systems for emerging AI workloads, focusing on how the data they consume and generate is managed and used. My work spans data systems for AI, scalable serving architectures, and methods for separating data and evaluation effects from model quality.

Previously, I was a Senior Researcher at [Apple](https://www.apple.com), a PostDoc at UZH ([DaST](https://www.ifi.uzh.ch/en/dast.html) with [Dan Olteanu](https://www.ifi.uzh.ch/en/dast/people/Olteanu.html)) and defended my thesis at [ETH](https://inf.ethz.ch)'s [Systems Group](https://systems.ethz.ch) with [Ce Zhang](https://zhangce.github.io).

**If you are interested in collaborating, please reach out directly. I also welcome motivated students at ETH for projects and theses. To apply, send me an email with your CV and transcript of records attached.**

<h2 class="mb-4">Research Focus Areas</h2>

<div class="accordion research-accordion" id="researchFocusAccordion">
  <div class="card">
    <div class="card-header" id="headingFocus1">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus1" aria-expanded="false" aria-controls="collapseFocus1">
          I. Data Systems for AI
        </button>
      </h5>
    </div>
    <div id="collapseFocus1" class="collapse" aria-labelledby="headingFocus1" data-parent="#researchFocusAccordion">
      <div class="card-body">
        I develop systems for efficiently organizing, maintaining, and retrieving data for AI applications, including scalable vector search. I also study how traces of interactions among users, models, and tools can be represented and learned from.
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFocus2">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus2" aria-expanded="false" aria-controls="collapseFocus2">
          II. Efficient AI Serving
        </button>
      </h5>
    </div>
    <div id="collapseFocus2" class="collapse" aria-labelledby="headingFocus2" data-parent="#researchFocusAccordion">
      <div class="card-body">
        I build scalable and resource-efficient architectures for serving emerging AI workloads. This work includes general mechanisms for execution and state management, as well as adaptive optimizations informed by workload and interaction signals.
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFocus3">
      <h5 class="mb-0">
        <button class="btn btn-link w-100" type="button" data-toggle="collapse" data-target="#collapseFocus3" aria-expanded="false" aria-controls="collapseFocus3">
          III. Data Quality & Evaluation
        </button>
      </h5>
    </div>
    <div id="collapseFocus3" class="collapse" aria-labelledby="headingFocus3" data-parent="#researchFocusAccordion">
      <div class="card-body">
        I study how data quality and evaluation choices influence observed AI-system performance during both evaluation and operation. My goal is to disentangle these effects from model quality and identify the underlying limitations of the complete AI system.
      </div>
    </div>
  </div>
</div>

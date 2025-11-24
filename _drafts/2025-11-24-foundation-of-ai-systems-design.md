---
layout: post
title: AI's Missing System Design Course
date: 2025-10-27 09:00:00+0100
description: Why AI Systems Design Needs a Seat in the University Curriculum
tags: AI SystemsDesign MLOps HigherEducation
categories: AISystemsDesignCourse
draft: true
chart:
  plotly: true
---

Disclaimer: _The views expressed in this post are completely my own and do not necessarily reflect the opinions of any current or former employers or academic institutions._

The pace of AI research today is breathtaking. Every month, we see dozens of papers introducing novel model architectures, new training techniques, and incremental gains in performance metrics. University curricula, rightly, focus on teaching students the fundamentals of these models: the mathematics of neural networks, the art of large-scale training, and the logic behind modern architectures. Yet, a critical gap exists between the lecture hall and the production environment. My experience has shown me that while we are excellent at _building_ models, we are dangerously ill-equipped to put them into production reliably and safely at scale. I strongly believe the current missing building block is educational. We need a fundamental shift in how we prepare the next generation of engineers and scientists to deploy AI.

#### The Great Divide: From Model Perfection to System Failure

Current research often operates under the assumption that improving the model, whether through bigger datasets or better algorithms, is the primary path to successful application. But practical success hinges on system-level robustness, not just point-in-time model accuracy. Many new practitioners, fresh out of programs focused on deep learning, are not fully aware of the fundamental limitations and complex behavior of the systems they are deploying. This deficit manifests in several ways, and these are just a few examples I've hand-picked based on my views and experience:

1. **Fundamental Limits (The Irreducible Error):** The best model in the world cannot outperform the inherent noise and ambiguity in the data itself. This is the irreducible error (or Bayes error). If the raw data only allows for 85% accuracy, targeting 95% is a fool's errand. We must train students to perform a feasibility study _before_ committing vast resources.
2. **Stochastic Behaviour and Data Drift:** AI models are inherently statistical and unpredictable. In production, unseen data drift is a constant threat. How do you monitor a model not just for _performance_ drops, but for statistical drift in its input distribution or concept?
3. **Error Propagation in Complex Pipelines:** The era of single-model deployment is over. We are increasingly building complex systems, notably involving Retrieval-Augmented Generation (RAG) and autonomous agents. When an error occurs -- whether a hallucination, a poor retrieval query, or a simple parsing failure -- it propagates and compounds through the pipeline, turning a small mistake into a catastrophic system failure. This requires thinking about system reliability, not just model reliability.

#### The Critical Need for a Mindset Shift

My own work, including contributions to projects like ease.ml/snoopy (feasibility studies for ML) and ease.ml/ci (statistical continuous integration), was dedicated to understanding and solving these production challenges from a research perspective. This work provided concrete frameworks for measuring fundamental limits and ensuring strong statistical guarantees in deployment. More recently, my research in advanced applications like Text-to-SQL reinforce the same lesson: a technically perfect model is useless if the system architecture around it is brittle, data quality is insufficent, or metrics are biased.

However, the reality is that tool-building and research alone are insufficient. The fundamental bottleneck remains the **mindset of the next generation of engineers and scientists**. We need to shift the focus from the constant, incremental improvement of single metrics and benchmarks to robust, reliable engineering and deployment of _systems_. This educational transformation must instill statistical rigor and systems-level thinking from day one, ensuring students are keenly aware of the stochastic nature of AI and the limitations of data quality or metrics. I don't believe that improving models alone, which is the main focus of tons of papers monthly, will in the short term enable more successful practical applications.

#### Advocating for the New Foundations of AI Systems Design

I believe that in the long term, all these concepts, including systems-level thinking, statistical guarantees, and operational reality, should be taught to students alongside the basics of AI/ML architectures and training. I strongly advocate for the creation of new university courses to address this gap. While I don't yet have the complete curriculum, lecture notes, slides, or exercises fully drafted, I want to start documenting concrete ideas and examples for such cases in a series of blog posts. To structure this initial ideation, I propose a set of topics that an essential curriculum, perhaps titled the _Foundations of AI Systems Design_, could cover:

- **Statistical Foundations for AI and ML Ops:** Understanding and estimating limitations of data quality, metrics, and distributional drift.
- **Robustness Engineering:** Techniques for designing systems resilient to stochastic model behavior and unexpected inputs.
- **Error Management in Complex Pipelines:** Modeling error propagation in multi-stage systems like RAG and multi-agent workflows.
- **Continuous Monitoring and Assurance:** Designing monitoring systems that track data quality, feature consumption, and model health, not just final output metrics.
- **Safety and Guardrails:** Implementing safety layers and constraints, such as query sanitization for generative systems.

By educating students in this holistic discipline, we can start bridging the gap between AI research excellence and real-world production reliability. We can move beyond model-centric thinking and start building truly reliable and powerful AI systems.

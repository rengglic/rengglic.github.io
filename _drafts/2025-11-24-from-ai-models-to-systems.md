---
layout: post
title: From AI Models to Systems
date: 2025-11-24 09:00:00
description: Reflections on the Future of AI Engineering
tags:
categories: AIEngineering, AISystemsDesign
draft: true
chart:
  plotly: true
---

To kick off the holiday season, I’m trying something new: writing down my thoughts in the form of a blog. My goal is not to present absolute truths but to share a perspective shaped by my very own personal experience, interests, and belief that deeper understanding matters—especially in an area currently driven by rapid empirical progress and still-limited theoretical grounding.

(_Note: While these reflections are informed by my professional experiences, the views expressed here are entirely my own._)

As I watch Artificial Intelligence move from research labs into complex production environments, I’ve been reflecting on how we prepare the next generation of scientists and engineers.

My perspective here is shaped by a combination of experiences: conducting my own research in this field, working alongside some of the world’s most qualified engineers in Big Tech, and teaching the newest developments in AI systems. Through actively reviewing and engaging with the latest research, I have noticed a growing convergence—and a gap—that I believe is critical to address.

We are currently in a golden age of modeling. We have excellent resources for teaching architecture, optimization, and representation learning. But based on my observations—both in industry and academia—I believe we are approaching a point where we need to expand that foundation.

To me, the path forward isn't just about building better models; it's about embracing AI Engineering and Systems Design.

**Why Education Must Lead Research**

Crucially, I view this gap as primarily an educational challenge rather than a purely research-driven one—at least in the immediate term.

While there is certainly fascinating research to be done in AI systems (and I actively review and participate in it), I believe our first priority must be to lay a common ground. We need to equip engineers, scientists, and future researchers with a shared mental model of how these systems behave in the wild.

In many cases, we don't need a novel algorithm to explain why a deployment failed; we need the foundational literacy to recognize the system dynamic at play. Before we can push the boundaries of research in this area, we need to codify the basics. We need to teach the "physics" of AI systems—how errors propagate, how data drifts, and how ambiguity resolves—so that the next generation has a stable platform to build upon.

**The Shift to Systems Thinking**

A full-fledged curriculum for this discipline is yet to be defined. However, to illustrate the kind of system dynamics I believe we need to teach, I draw on specific examples from my own research and professional experience.

When I try to make AI work in the real world, the failure modes rarely come down to the choice of the neural network alone. They usually stem from system-level interactions:

- The Ambiguity in Text-to-SQL: In my work with Text-to-SQL, I’ve found that the bottleneck is rarely just the reasoning capability of the LLM. More often, it’s the ambiguity of the database schema itself. The lesson here isn't just about model fine-tuning; it's about understanding how to design systems that handle vague definitions.
- The RAG Cascade: With Retrieval-Augmented Generation, I’ve observed that "better" components don't always yield better results. A slight imperfection in the retrieval step can propagate through the pipeline, leading the generator to hallucinate. Students need to understand this not as a bug, but as a standard property of cascading systems.
- CI/CD and The Definition of Success: Even the way we test software changes with AI. In traditional engineering, a test passes or fails. In AI systems, I've found we need to reason about data drift, performance variance, and statistical significance. A "failing" build might just be noise, or it might be a signal of fundamental drift.

**A Vision for "Limitation Literacy"**

Drawing from my time teaching these concepts, I believe there is an opportunity to complement our current educational approach with what I call "Limitation Literacy."

Moving forward, I think it would be incredibly valuable to foster a curriculum where students learn to design systems with a clear-eyed understanding of their constraints. It’s about teaching the intuition for how components interact, how data quality shapes behavior, and how errors accumulate.

By establishing this educational baseline, we pave the way for more meaningful future research. When researchers understand the system-level constraints deeply, they can invent solutions that address the root causes rather than just the symptoms.

**Next Steps**

I want to contribute to this educational layer, starting small but practical.

In the near future, I plan to write a series of blog posts that explore these system-level dynamics in detail—using simple, reproducible setups to illustrate things like schema ambiguity or metric instability.

My hope is that these posts can serve as the first step—a foundation of concrete examples that might eventually evolve into a more mature curriculum, spanning books, lecture notes, and exercises. It is a long-term goal, but one that I believe is essential for the future of robust AI engineering.

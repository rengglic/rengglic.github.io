---
layout: post
title: Controlled Retrieval Data Quality in AI Pipelines
date: 2025-11-20 09:00:00
description: Messy thought around RAG, semantic+structured search, vector databases, and data quality
tags: RAG, VectorDB, DataQuality, Text2SQL
categories: AIEngineering, AISystemsDesign
draft: true
chart:
  plotly: true
toc: true
---

To kick off the holiday season, I’m trying something new: writing down my thoughts in the form of a blog.
This blog will explore the current techniques and challenges involved in building production-ready AI systems. I’ll look at the field from multiple angles—from high-level questions about the limitations and implications of using AI/ML in the first place, to engineering and system-design best practices, all the way down to low-level open research problems.
What motivated me to start this blog is a noticeable gap in educational material that explains the fundamental and principled aspects of this fast-moving field across all levels (management, engineering, research) and disciplines (AI, computing systems, data management). My goal is not to present absolute truths but to share a perspective shaped by my very own personal experience, interests, and belief that deeper understanding matters—especially in an area currently driven by rapid empirical progress and still-limited theoretical grounding.

**RAG and the Quest for Controlled Retrieval Quality**

The first post will focus on the current state of retrieval-augmented generation (RAG) pipelines, specifically, the retrieval component. I’ll go into deeper technical and visionary details, some of which I’ve deliberately left out here, in separate follow-up posts.

**What is a RAG pipeline?**

_TBD_

**Motivation: Do we even need RAG in the near future?**

There are two common arguments from critics who claim we may not need to invest heavily in improving RAG pipelines:

1. LLMs will have ever-increasing context windows and capabilities.
2. In the near future, the belief goes, we’ll simply place all relevant data directly into the prompt. (AI) agents will iteratively fix retrieval issues. If agents can refine queries, reason about missing information, and recover from poor retrieval automatically, then perhaps controlled retrieval quality becomes unnecessary.

**Tentative Follow-up Posts (A Technical and Visionary Roadmap)**

A tentative list of upcoming posts includes (not necessarily in order):

- Technical: Filtered Semantic Search — What Is the Right Abstraction?
- Technical: Faster Dense Retrieval — IVF vs. HNSW
- Vision: Automatically Optimizing (Filtered) Vector Search

---
layout: post
title: An Operational Data Quality View on RAG Pipelines
date: 2025-11-20 09:00:00
description: Messy thought around RAG, semantic+structured search, vector databases, and data quality
tags:
categories: RAG, VectorDB, DataQuality, Text2SQL
draft: true
chart:
  plotly: true
toc: true
---

To kick off the holiday seasons I wanted to write down my thoughts on the current stage of retrieval augmented generation (RAG) and especially the _retrieval_ part of it.
This post is not necessarely the truth, but merely my somewhat biased view on the topic based on my experience, interrests, and deeper believes aligned with my intrisinc motivation to understand a
field that is currenlty dominated by empirical progress and little fundamental understanding.

This blog serves as an overview of the main challenges I currently see in the field. I will dvelve into more details for each topic in separat blog posts in the near future. A tentative list of followup blog posts is the following (not necessarily in order of apperence):

- Filtered Semantic Search: What is the right abstraction?
- Faster Dense Retrieval: IVF vs. HNSW
- On Automatically Optimizing (Filtered) Vector Search

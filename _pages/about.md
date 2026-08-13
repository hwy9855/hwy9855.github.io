---
layout: about
title: about
permalink: /
subtitle: PhD Candidate in Natural Language Processing · <a href='https://www.ed.ac.uk/informatics'>University of Edinburgh</a>

profile:
  align: right
  image: wenyu_profile.jpg
  image_circular: false # crops the image to make it circular
  size: small

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts
---

I am a final-year PhD candidate in Natural Language Processing at the University of Edinburgh, advised by [Prof. Jeff Z. Pan](https://homepages.inf.ed.ac.uk/jpan/) and [Prof. Mirella Lapata](https://homepages.inf.ed.ac.uk/mlap/). I study how language models can **retrieve, retain, and reason with external information**. My research connects retrieval-augmented generation (RAG), non-parametric memory, multi-hop question answering, and LLM agents, with an emphasis on making knowledge-intensive systems more efficient and reliable.

During my PhD, I have been a research intern at [Microsoft Research Cambridge](https://www.microsoft.com/en-us/research/lab/microsoft-research-cambridge/) working with [John Winn](https://www.microsoft.com/en-us/research/people/jwinn/) on memory-augmented language modeling, and at Huawei UK on reinforcement learning for language-model agents and large-scale entity alignment. My work has appeared at ACL, EMNLP, SIGIR, IJCNLP-AACL, and _Knowledge-Based Systems_, including an ACL 2025 oral paper.

<div class="clearfix"></div>

<div class="alert alert-primary" role="alert" markdown="1">
**I am currently seeking full-time research positions, including Research Scientist, Applied Scientist, and postdoctoral roles.** I am particularly interested in LLM pretraining and post-training, RAG, memory-augmented systems, and reinforcement learning for LLM agents. [View my CV](/assets/pdf/cv.pdf) or [get in touch](mailto:w.huang@ed.ac.uk).
</div>

## Research

My work is organized around a central question: **how can language models use external information as reliable memory for reasoning?**

- **Retrieve compact, useful evidence.** I introduced generative subgraph retrieval for knowledge-graph RAG: a 220M-parameter retriever is competitive with 7B-parameter baselines, while a 3B retriever-reader system established state-of-the-art results on WebQSP and CWQ ([paper](https://aclanthology.org/2024.findings-emnlp.927/), [code](https://github.com/hwy9855/GSR)). In complementary work, the LTGen benchmark tests RAG over long-tail facts and identifies when knowledge-graph evidence is more effective than passage retrieval ([paper](https://doi.org/10.1016/j.knosys.2025.113648)).

- **Reason across multiple pieces of evidence.** My ACL 2025 oral paper studies how context order and causal masking affect multi-hop question answering. It shows that aligning evidence with the reasoning chain matters and that bidirectional attention can improve decoder-only models ([paper](https://aclanthology.org/2025.acl-long.869/), [code](https://github.com/hwy9855/MultiHopQA-Reasoning)).

- **Retain and use knowledge over time.** I co-developed a taxonomy of AI memory representations and operations ([survey](https://arxiv.org/abs/2505.00675)). Recent collaborations extend this direction to [temporal reasoning in multi-session agents](https://iclr.cc/virtual/2026/poster/10006811) and [stateful tool use in multi-turn dialogue](https://aclanthology.org/2025.findings-acl.284/).

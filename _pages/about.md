---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

# Junteng Liu

I am a first-year PhD candidate in Computer Science at the [HKUST NLP Group](https://nlp.cse.ust.hk/), Hong Kong University of Science and Technology, advised by Prof. Junxian He. My research focuses on **natural language processing** and **machine learning**.

## Academic Background

- **Ph.D. in Computer Science** — Hong Kong University of Science and Technology, 2024–Present
- **B.Eng.** — Shanghai Jiao Tong University, 2020–2024 (graduated June 2024)

## Research Experience

- **Research Intern**, MINIMAX — February 2025 – Present
- **Research Intern**, Tencent WXG — June 2024 – September 2024 (advised by Zifei Shan)
- **Research Intern**, Shanghai AI Lab — June 2023 – December 2023 (advised by Prof. Yu Cheng)

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM truthfulness and Interpretability

## Skills

- Natural Language Processing
- Machine Learning
- LLM Reasoning & Reinforcement Learning
- Hallucination in Vision-Language Models
- LLM Truthfulness & Interpretability

## Contact

- **Email**: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub**: [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar**: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter)**: [@junteng88716710](https://x.com/junteng88716710)

## Publications

{% for post in site.publications reversed %}
* **{{ post.title }}** — {{ post.venue }}, {{ post.date | date: "%Y" }}. {% if post.paperurl %}[[Paper]({{ post.paperurl }})] {% endif %}{% if post.citation %}{{ post.citation }}{% endif %}
{% endfor %}

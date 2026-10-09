---
permalink: /
title: "About Me"
excerpt: "Junjia Qi — LLM agents, agent memory, agentic programming, and multimodal GUI agents."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am currently a final-year Master's student at the College of Computing & Data Science, City University of Hong Kong (CityU), supervised by Prof. Xiangyu Zhao. Prior to this, I received my B.Eng. degree in Computer Science and Technology from Jinan University in 2025, with English as the medium of instruction.

My research interests broadly lie in **LLM-based intelligent agents and agentic systems**. My recent work explores **agentic programming, self-evolving agentic workflows, long-term memory for agents, and multimodal GUI agents**. More broadly, I am interested in building capable, adaptive, and reliable AI agents and exploring their applications in complex, real-world environments.

I am actively seeking **PhD and Research Assistant opportunities** and am open to research collaborations in related areas. Please feel free to reach out!

[Publications]({{ '/publications/' | relative_url }}) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=vuviavMAAAAJ) · [GitHub](https://github.com/Qi202) · [Email](mailto:junjiaqi2-c@my.cityu.edu.hk)

Education
======

<ul class="education-list">
  <li class="education-item">
    <svg class="education-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 3 1 9l4 2.18v6L12 21l7-3.82v-6L21 10.09V17h2V9L12 3Zm6.91 6L12 12.77 5.09 9 12 5.23 18.91 9ZM17 15.99l-5 2.73-5-2.73v-3.72L12 15l5-2.73v3.72Z"/></svg>
    <div class="education-description">
      <p class="education-course">M.Sc. in Data Science, College of Computing &amp; Data Science<br>Sep. 2025 – Oct. 2026 (Expected)</p>
      <p class="education-institution">City University of Hong Kong, Kowloon, Hong Kong</p>
    </div>
  </li>
  <li class="education-item">
    <svg class="education-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 3 1 9l4 2.18v6L12 21l7-3.82v-6L21 10.09V17h2V9L12 3Zm6.91 6L12 12.77 5.09 9 12 5.23 18.91 9ZM17 15.99l-5 2.73-5-2.73v-3.72L12 15l5-2.73v3.72Z"/></svg>
    <div class="education-description">
      <p class="education-course">B.Eng. in Computer Science and Technology<br>Sep. 2021 – Jun. 2025</p>
      <p class="education-institution">Jinan University (JNU), Guangzhou, China</p>
    </div>
  </li>
</ul>

Selected Publications
======

**[LLM-as-Code: Agentic Programming for Agent Harness](https://arxiv.org/abs/2606.15874)**<br>
**Junjia Qi** (co-first author), Zichuan Fu, Jingtong Gao, Wenlin Zhang, Hanyu Yan, Xian Wu, and Xiangyu Zhao.<br>
*KDD 2026 Workshop on Agentic Software Engineering (AgenticSE).* Accepted.

The framework puts looping, branching, and sequencing under program control while invoking LLMs for reasoning and generation. It builds context from a call-tree DAG and studies the approach through a computer-use agent case study.

[Paper](https://arxiv.org/abs/2606.15874) · [Code](https://github.com/Fzkuji/OpenProgram) · [Details]({{ '/publication/2026-06-14-llm-as-code' | relative_url }})

### Additional Manuscripts

- **[GUI-Lens: Coarse-to-Fine Cropping for GUI Grounding with General-Purpose VLMs](https://arxiv.org/abs/2608.03270)** — arXiv preprint, 2026. [Details]({{ '/publication/2026-08-04-gui-lens' | relative_url }}).
- **Self-Evolving Agentic Workflows via Semantic Decomposition of Complex Tasks** — under review at the NeurIPS 2026 Workshop on Interpreting Agent Behavior (IAB), Competition Paper Track. [Details]({{ '/publication/2026-09-05-self-evolving-agentic-workflows' | relative_url }}).

Selected Projects
======

### Scriptorium — Traceable Long-Term Memory for AI Agents

I contribute to a collaborative agent memory project that stores knowledge as editable Markdown notes, with citations linking individual statements to archived source messages. The system supports retrieval, project and global memory layers, and access through MCP; atomic updates validate citations and references before committing changes.

[Code & documentation](https://github.com/Fzkuji/Scriptorium)

### Qiyuan (岐源) — Domain-Specific LLM Fine-Tuning and RAG

For my undergraduate thesis, I built a traditional Chinese medicine question-answering system combining Baichuan2-7B fine-tuning with hybrid retrieval and reranking. I curated **11,540 dialogue examples** and used **4-bit QLoRA on a single RTX 4090 (24 GB)**. In the thesis evaluation on **CMB-Clin**, the full system achieved **ROUGE-L 21.18**, compared with **10.68** for the base model.

Honors and Awards
======

<ul class="honors-list">
  <li class="honors-item">
    <i class="fas fa-award honors-icon" aria-hidden="true"></i>
    <div>
      <p class="honors-title"><strong>1st Place, Agent Track, <a href="https://glee-competition.com/leaderboard">GLEE Competition</a></strong> — Agent “grok 4.6”</p>
      <p class="honors-date">Aug. 2026</p>
    </div>
  </li>
  <li class="honors-item">
    <i class="fas fa-award honors-icon" aria-hidden="true"></i>
    <div>
      <p class="honors-title"><strong>Outstanding Undergraduate Thesis Award of Jinan University</strong> (Top 1%)</p>
      <p class="honors-date">Jun. 2025</p>
    </div>
  </li>
</ul>

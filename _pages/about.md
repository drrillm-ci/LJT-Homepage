---
permalink: /
title: "About"
---

## Selected Publications

The latest publications (also listed on the [publications]({{ '/publications/' | relative_url }}) subpage):

{% for pub in site.publications %}
  {% assign loop_index = forloop.index %}
  {% if loop_index > 6 %}{% break %}{% endif %}
  {% if pub.citation %}
  <div class="publication">
    <p>{{ pub.citation | remove: '&quot;' | remove: '&quot;' }}
    {% if pub.paperurl %}
      &nbsp;<a href="{{ pub.paperurl }}" target="_blank">[Paper]</a>
    {% endif %}
    {% if pub.permalink %}
      &nbsp;<a href="{{ pub.permalink | relative_url }}">[Details]</a>
    {% endif %}
    </p>
  </div>
  {% endif %}
{% endfor %}

See the full list on the [publications page]({{ '/publications/' | relative_url }}).

## About Me

I am a first-year Ph.D. candidate at the **[HKUST NLP Group](https://hkust-nlp.github.io/)**,
supervised by **[Prof. Junxian He](https://jxhe.github.io/)**. My research focuses on
**natural language processing and machine learning**. Before starting my Ph.D., I graduated from
**Shanghai Jiao Tong University (SJTU)** in June 2024, where I was also advised by Prof. Junxian He
during my undergraduate studies.

## Research Interests

My research interests include:

- **LLM Reasoning and Reinforcement Learning** — synthesizing verifiable reasoning data and
  learning reasoning capabilities of large language models.
- **Hallucination in Vision-Language Models (VLM)** — understanding and mitigating perception
  bottlenecks and hallucination problems in VLMs, especially for chart understanding.
- **LLM Truthfulness and Interpretability** — probing the internal representations of LLMs to
  understand, measure, and improve their truthfulness.

## Education

- **Ph.D. in Computer Science** (2024 – Present)
  Hong Kong University of Science and Technology (HKUST)
- **B.Eng.** (2020 – 2024)
  Shanghai Jiao Tong University (SJTU)

## Research Experience

- **Research Intern**, MINIMAX (February 2025 – Present)
- **Research Intern**, Tencent WXG (June 2024 – September 2024) — advised by Zifei Shan
- **Research Intern**, Shanghai AI Lab (June 2023 – December 2023) — advised by Prof. Yu Cheng

## Awards

- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://x.com/junteng88716710)

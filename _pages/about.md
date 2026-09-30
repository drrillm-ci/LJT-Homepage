---
permalink: /
title: "About"
---

## About Me

- First-year PhD candidate at HKUST NLP Group.
- Graduated from Shanghai Jiao Tong University (SJTU) in June 2024.
- Research focuses on natural language processing and machine learning.

## Publications

In addition to the full list on the dedicated [publications]({{ '/publications/' | relative_url }})
subpage, my publications are also recorded here in the About section:

{% for pub in site.publications %}
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

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM truthfulness and Interpretability

## Education

- Ph.D. in Computer Science (2024–Present), Hong Kong University of Science and Technology
- B.Eng. (2020–2024), Shanghai Jiao Tong University

## Research Experience

- Research Intern at MINIMAX (February 2025 – Present)
- Research Intern at Tencent WXG (June 2024 – September 2024)
- Research Intern at Shanghai AI Lab (June 2023 – December 2023)

## Awards

- Zhiyuan Honor Scholarship at Shanghai Jiao Tong University

## Contact

- Email: jliugi@connect.ust.hk
- GitHub: https://github.com/Vicent0205
- Google Scholar: https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate
- X (Twitter): @junteng88716710

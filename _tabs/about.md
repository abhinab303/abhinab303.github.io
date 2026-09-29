---
icon: fas fa-info-circle
order: 4
description: >-
  Final-year Computer Science Ph.D. student at RIT and ML/AI Co-op at Wasabi
  Technologies. Research, publications, industry experience, mentoring, and service.
---

{% include profile-intro.html %}

## Current industry work

{% include industry-work.html %}

## Publications

{% for paper in site.data.research.publications %}
{% include research-entry.html paper=paper %}
{% endfor %}

## Ongoing research

{% assign robustness = site.data.research.projects | where: 'id', 'robust-peft' | first %}
{% include research-entry.html paper=robustness %}

## Research mentoring

{% assign mentoring = site.data.research.projects | where: 'id', 'video-anomaly-detection' | first %}
{% include research-entry.html paper=mentoring %}

## Experience & education

- **Research Assistant, Rochester Institute of Technology** · August 2022–present. Research in data selection, generative augmentation, multimodal continual learning, and robust adaptation of foundation models.
- **R&D Software Engineer, North Star Developer’s Village** · 2019–2022. Developed machine learning solutions for clinical-note text classification and server-side functionality for remote learning platforms used by **50+ universities**.
- **Ph.D. in Computer Science, Rochester Institute of Technology** · August 2022–present; expected **May 2027**. Coursework includes statistical machine learning, deep learning, data-driven knowledge discovery, and non-convex optimization.
- **Bachelor’s in Electrical Engineering, Tribhuvan University** · 2013–2017, Lalitpur, Nepal.

## Projects, teaching & leadership

- **Data science learning platform, RIT.** Built a Flask, React, and MongoDB platform for Principles of Computing Immersion, supporting **100+ students**, and supervised its undergraduate contributors.
- **Teaching Assistant, RIT** · 2023–2024. Led labs, graded coursework, and mentored students in Machine Learning, Computer Science, and Database Systems.
- **Team Manager, North Star Developer’s Village** · 2022. Managed three developers researching and building educational robots.
- **Robotics Team Leader, Tribhuvan University** · 2015–2017. Led the university team at ABU ROBOCON 2016 in Thailand.

## Service & recognition

- **Silver Reviewer Award, ICML 2026**, recognizing strong reviews based on area-chair ratings.
- **Conference reviewing:** 31 papers across NeurIPS 2025 and 2026, ICML 2026, AAAI 2026 and 2027, ICLR 2026, CVPR 2026, ECCV 2026, and AISTATS 2026.
- **Journal reviewing:** IEEE Transactions on Services Computing (2024) and TMLR (2026).
- **Additional service:** IJCAI 2026, IEEE Big Data 2024, and ACM AI Summit 2026.
- **Upcoming reviewer service:** ICLR 2027 and AISTATS 2027.
- **Best Engineering and Panasonic Awards, ABU ROBOCON 2016**, with the Tribhuvan University team.

## Selected talks

- **Data-Efficient Deep Learning** · GCCIS PhD Colloquium Series, RIT, November 2024.
- **BOSS: Size-Aware One-shot Subset Selection** · Poster presentation at ICML 2024, July 2024.

## Tools & methods

I work with PyTorch, scikit-learn, CLIP, Stable Diffusion, vision transformers, and multimodal models. For LLM inference, my toolkit includes NVIDIA Dynamo, LMCache, SGLang, vLLM, TensorRT-LLM, and cloud storage. My main programming languages include Python, C/C++, JavaScript, and SQL.

[Download my resume]({{ '/assets/files/cv.pdf' | relative_url }}) for the complete experience, skills, and publication list.

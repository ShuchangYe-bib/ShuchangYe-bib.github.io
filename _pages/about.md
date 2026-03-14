---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate in Engineering at the University of Sydney, specializing in multimodal learning. I hold a Bachelor of Advanced Computing (Honours) in Computer Science and Computational Data Science from the University of Sydney (GPA 3.91/4.00, First-Class Honours, top 1%) and am supported by an Australian Government RTP Scholarship. During my undergraduate studies, I received the Ian Jackson Memorial Prize, was named a Dalyell Scholar, and consistently appeared on the Dean’s List.

My research on multimodal learning mainly focuses on:

(1) Multimodal collaborative decision-making (e.g., PET-CT with electronic health record);

(2) Cross-modality assisted learning (e.g., language-guided vision tasks);

(3) Multimodal generative methods for diagnostic support (e.g., medical visual question answering, radiology report generation).

# 🔥 News
- *2025.10*: A paper on medical report generation is accepted to **TMM**
- *2025.03*: A paper on textual reliance is accepted to **ICCV 2025**
- *2024.10*: A paper on modality preference bias is accepted to the workshop in **ACM MM 2024**
- *2024.05*: A paper on medical language-guided segmentation is accepted to **MICCAI 2024**
- *2024.03*: I commenced my PhD in Engineering at the University of Sydney, focusing on multimodal learning and funded by an Australian Government RTP Scholarship.
- *2023.12*: I graduated from the University of Sydney with a Bachelor of Advanced Computing (First Class Honours; WAM 95+)
- *2021.01*: I was invited to be a Dalyell Scholar. 
- *2022.09*: I joined The University of Sydney as a research assistant.
- *2022.02*: I participate in ICPC on behalf of The University of Sydney

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM</div><img src='images/dtrace.png' alt="dtrace" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Traceback Learning for Medical Report Generation](https://arxiv.org/abs/2401.13267)

**Shuchang Ye**, Mingyuan Meng, Mingjian Li, Dagan Feng, Usman Naseem, Jinman Kim

[**Website**](https://shuchangye-bib.github.io/websites/DTrace/dtrace.html)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/prolearn.png' alt="prolearn" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Alleviating Textual Reliance in Medical Language-guided Segmentation
via Prototype-driven Semantic Approximation](https://arxiv.org/abs/2507.11055)

**Shuchang Ye**, Usman Naseem, Mingyuan Meng, Jinman Kim

[**Website**](https://shuchangye-bib.github.io/websites/ProLearn/prolearn.html)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/medcfvqa.png' alt="sgseg" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Causal Approach to Mitigate Modality Preference Bias in Medical Visual Question Answering](https://dl.acm.org/doi/abs/10.1145/3689096.3689459)

**Shuchang Ye**, Usman Naseem, Mingyuan Meng, Dagan Feng, Jinman Kim

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/sgseg.png' alt="sgseg" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enabling Text-Free Inference in Language-Guided Segmentation of Chest X-Rays via Self-guidance](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_23)

**Shuchang Ye**, Mingyuan Meng, Mingjian Li, Dagan Feng, Jinman Kim

[**Website**](https://shuchangye-bib.github.io/websites/SGSeg/sgseg.html)

</div>
</div>

# 🎖 Honors and Awards
- *2024.03* Australia Government RTP Scholarship.
- *2023.09* Dean's List excellence in academic performance
- *2023.07* The Ian Jackson Memorial Prize for Computer Science
- *2021.01* Dalyell Scholar

# 📖 Educations
- *2024.03 - Present*, Doctor of Philosophy (Engineering), The University of Sydney
  - Thesis: Multimodal Learning 
- *2020.03 – 2024.03*: Bachelor of Advanced Computing (Honours), The University of Sydney
  - Major: Computer Science, Computational Data Science


# 💻 Work Experience
- *2026.01 - Present*, Machine Learning Engineer, [TikTok (ByteDance)](https://www.tiktok.com/), Sydney, Australia
  - 0->1 development of TikTok's first Audio-Visual-Language foundation model (AVLM) for video and live moderation: data pipeline, pre-training, post-training, and downstream supervised fine-tuning and alignment.
  - Deployed to production moderation systems, significantly reducing Community Guidelines Violation Rate (CGVR) and Creator Overkill Rate (COR) compared to existing ASR+VLM approach.
- *2022.07 - 2022.12*, Research Assistant, [The University of Sydney](https://www.sydney.edu.au), Sydney, Australia
  - Built the first facial recognition system for animals, demonstrating the potential to replace traditional and widely used tagging methods. [PDF](https://plf.tennessee.edu/wp-content/uploads/sites/229/2024/01/Identification-of-cattle-facial-features-via-deep-learning.pdf)
  - Key areas: computer vision, object detection, convolutional neural networks, and facial recognition.

# 📜 Reviewer Certificates
- *2025*, IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), [Certificate]({{ '/certificates/TPAMI%20reviewer%20certificate%202025.pdf' | relative_url }})

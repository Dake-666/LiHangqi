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
<!-- # Oop! I am updating this page. Please come back later. 😄 -->
<span class='anchor' id='about-me'></span>
# 💬 About Me

<!-- Hi! My name is Xinyu Yang (杨心妤), a first-year Information Science PhD student at Cornell University, advised by [Prof. Yian Yin](https://www.yianyin.net/). I am broadly interested in Data Science, Network Science, Machine Learning and Science of Science. At present, my focus lies in conducting large-scale scientific data analyses using cutting-edge computational and machine learning techniques. -->

Hi! My name is Xinyu Yang (杨心妤), a first-year Information Science PhD student at Cornell University, advised by [Prof. Yian Yin](https://www.yianyin.net/). I am broadly interested in Applied Machine Learning, Data Science and AI for Common Good. Previously, I got my bachelor's degree in Computer Science and Technology from Zhejiang University, China. During my undergraduate, I was fortunate to be a research intern at [Stanford AI Lab](https://ai.stanford.edu/) advised by [Prof. James Zou](https://www.james-zou.com/). I also experienced a wonderful research internship at Zhejiang University Digital Media Computing and Design (DCD) Lab advised by [Prof. Fei Wu](https://scholar.google.com/citations?user=XJLn4MYAAAAJ&hl=en).


# 📖 Educations
- *2023.08 - Present* Ph.D. in Information Science, Cornell University, Ithaca, NY, USA
- *2019.09 - 2023.06* B.E. in Computer Science and Technology, Zhejiang University, Hangzhou, China
  <!-- - *Minor:* Advanced Honor Class of Engineering Education Program (Honors program of Zhejiang University) -->


<!-- 
# 🔥 News
- Working on a project jointly advised by [Prof. James Zou](https://www.james-zou.com/) (Stanford Univeristy) and [Dr. Nazneen Rajani](https://www.nazneenrajani.com/) (Hugging Face). Will submit soon. -->


# 📝 Publications and Preprints

\* denotes equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/dataset_card.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Navigating Dataset Documentation in AI: A Large-Scale Analysis of Dataset Cards on Hugging Face**

**Xinyu Yang\***, [Weixin Liang\*](https://ai.stanford.edu/~wxliang/), [James Zou](https://www.james-zou.com/)

***ICLR 2024***

<!-- ***NeurIPS 2023 Workshop on [Regulatable ML](https://regulatableml.github.io/#overview)*** -->

[[PDF]](https://arxiv.org/abs/2401.13822.pdf), [[Code]](https://github.com/YoungXinyu1802/HuggingFace-Dataset-Card-Analysis)


- We present a comprehensive large-scale analysis of 7,433 ML dataset documentation on Hugging Face.
- Based on our research findings, we emphasize the importance of comprehensive dataset documentation and offer suggestions to practitioners on how to write documentation that promotes reproducibility, transparency, and accessibility of their datasets, which can help to improve the overall quality and usability of the dataset community.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Machine Intelligence 2024</div><img src='images/modelcard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**What's documented in AI? Systematic Analysis of 32K AI Model Cards**

[Weixin Liang\*](https://ai.stanford.edu/~wxliang/), [Nazneen Rajani\*](https://www.nazneenrajani.com/), **Xinyu Yang\***, [Ezinwanne Ozoani](https://www.linkedin.cn/incareer/in/ezi-ozoani), [Eric Wu](https://ericwu09.github.io/), [Yiqun Chen](https://yiqunchen.github.io/), [Daniel Scott Smith](https://www.danielscottsmith.com/), [James Zou](https://www.james-zou.com/)

***Nature Machine Intelligence 2024***


[[PDF]](https://www.nature.com/articles/s42256-024-00857-z.epdf?sharing_token=t60q8xz8Qfw70UsZXMUmhtRgN0jAjWel9jnR3ZoTv0O6DtFA7RtfK0nfhKseaTom13GSX6MC9Qv0cuMQe_cCWMU-IzVs2qfzeSGJM3lzA8Dpg0JfmTzdNelnC7Mjd6N0EliE4e93iMohI9QKOpMc0b8qja6829UtwfB-ctlULG8%3D), [[Code]](https://github.com/Weixin-Liang/AI-model-card-analysis-HuggingFace)


- We conduct a comprehensive analysis of 32,111 AI model documentations on Hugging Face, which provides a systematic assessment of community norms and practices around model documentation through large-scale data science and linguistic analysis. 
- Our findings reveal that while most popular models have model cards, they often vary in detail. Sections on environmental impact, limitations, and evaluation are frequently incomplete, whereas training details are more consistently provided. We also analyze the content of each section to characterize practitioners' priorities.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NEJM AI 2024</div><img src='images/ai-reviewer.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Can large language models provide useful feedback on research papers? A large-scale empirical analysis**

[Weixin Liang\*](https://ai.stanford.edu/~wxliang/), [Yuhui Zhang\*](https://cs.stanford.edu/~yuhuiz/), [Hancheng Cao\*](http://hanchengcao.me/), Binglu Wang, Daisy Ding, **Xinyu Yang**, [Kailas Vodrahalli](http://stanford.edu/~kailasv/about.html), [Siyu He](https://he-siyu.github.io/), [Daniel Smith](https://www.danielscottsmith.com/), [Yian Yin](https://www.yianyin.net/), [Daniel A. McFarland](https://ed.stanford.edu/faculty/mcfarland), [James Zou](https://www.james-zou.com/)
<!-- ( * equal contribution) -->

***NEJM AI 2024***

[[PDF]](https://ai.nejm.org/doi/full/10.1056/AIoa2400196), [[Twitter]](https://twitter.com/james_y_zou/status/1709608909395357946), [[Code]](https://github.com/Weixin-Liang/LLM-scientific-feedback)


- We created an automated pipeline using GPT-4 to provide comments on the full PDFs of scientific papers. 
- Our results suggest that LLM and human feedback can complement each other. While human expert review is and should continue to be the foundation of rigorous scientific process, LLM feedback could benefit researchers, especially when timely expert feedback is not available and in earlier stages of manuscript preparation before peer-review.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023</div><img src='images/Dunhuang.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Reconnecting the Broken Civilization: Patchwork Integration of Fragments from Ancient Manuscripts**

Yuqing Zhang\*, Zhou Fang\*, **Xinyu Yang\***, [Shengyu Zhang](https://shengyuzhang.github.io/), Baoyi He, Huaiyong Dou, [Junchi Yan](https://scholar.google.com/citations?user=ga230VoAAAAJ&hl=en), Yongquan Zhang, [Fei Wu](https://scholar.google.com/citations?user=XJLn4MYAAAAJ&hl=en)
<!-- ( * equal contribution) -->

***ACM MM 2023*** <span style="color:red">***(Oral)***</span>

[[PDF]](https://dl.acm.org/doi/10.1145/3581783.3613804)

- We developed a multimodal pipeline for Dunhuang manuscript fragments reconstruction, leveraging text-based localization and a self-supervised contour matching framework, accompanied by a global reconstruction process. Our empirical evaluations reveal that this pipeline exhibits a remarkable success rate in fragment assembly.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/moonshape.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Accuracy on the Curve: On the Nonlinear Correlation of ML Performance Between Data Subpopulation**

[Weixin Liang\*](https://ai.stanford.edu/~wxliang/), [Yining Mao\*](https://yining-mao.github.io/), [Yongchan Kwon\*](https://www.yongchanstat.com/), **Xinyu Yang**, [James Zou](https://www.james-zou.com/)
<!-- ( * equal contribution) -->

***ICML 2023***

<!-- **ICML 2022** Workshop on [Principles of Distribution Shift](https://sites.google.com/view/icml-2022-pods/)

**ICML 2022** Workshop on [Spurious Correlations, Invariance, and Stability](https://sites.google.com/view/scis-workshop/) -->

[[PDF]](https://arxiv.org/pdf/2305.02995.pdf), [[Website]](https://moonshape.readthedocs.io/), [[Video]](https://slideslive.com/38986287/on-the-nonlinear-correlation-of-ml-performance-berween-data-subpopulations), [[Code]](https://github.com/yining-mao/Moon-Shape-ICML-2023)

- We show that there is a “moon shape” correlation (parabolic uptrend curve) between the test performance on the majority subpopulation and the minority subpopulation.
This nonlinear correlations hold across model architectures, training settings, datasets, and the imbalance between subpopulations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2022 Workshop</div><img src='images/MetaShift.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

 **MetaShift: A Dataset of Datasets for Evaluating Contextual Distribution Shifts**

[Weixin Liang\*](https://ai.stanford.edu/~wxliang/), **Xinyu Yang\***, [James Zou](https://www.james-zou.com/)
<!-- ( * equal contribution) -->

<span style="color:red">***Contributed Talk***</span> at ***ICML 2022*** Workshop on [Shift happens: Crowdsourcing metrics and test datasets beyond
ImageNet](https://shift-happens-benchmark.github.io/)

[[PDF]](https://openreview.net/forum?id=iuSDDiqacPj), [[Website]](https://metadataset.readthedocs.io/), [[Video]](https://slideslive.com/38987455/metashift-a-dataset-of-datasets-for-evaluating-contextual-distribution-shifts), [[Code]](https://github.com/YoungXinyu1802/icml-2022/tree/main/shifthappens/tasks/imagenet_metashift)


- MetaShift introduces a collection of >10K sets of images with annotated contexts. It enables evaluating how ML works in different contexts (e.g. indoor cat vs outdoor cat). 
- We provided a distance score that measures the amount of distribution shift between any two of the data sets.
- We presented methods to match labels to ImageNet hierarchy via WordNet ID and construct classification tasks over MetaShift to enable evaluating off-the-shelf ImageNet models.
</div>
</div>


# 🎖 Honors and Awards
- *2022 - 2023* Outstanding Graduates of Zhejiang Province
- *2022 - 2023* Outstanding Graduates of Zhejiang University
- *2021 – 2022* First-Class Scholarship for Outstanding Students of Zhejiang University (Top 3%)
- *2020 – 2021* Second-Class Scholarship for Outstanding Students of Zhejiang University (Top 8%)
- *2019 – 2020* National Scholarship (Top 1%)
- *2019 – 2020* First-Class Scholarship for Outstanding Students of Zhejiang University (Top 3%) 
- *2019 – 2020* Outstanding Student Awards in Yunfeng College (15 out of 800 students) 

# 🗒 Teaching
- *Spring 2023* Python Programming, Zhejiang University, Teaching Assistant

<!-- # 💬 💻Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 🎉 Misc
- I started learning Chinese Calligraphy (a traditional form of writing characters from the Chinese language through the use of ink and a brush) and sketchy when I was nine. [\[Gallery\]](images/gallery.png)
- I love art and sports. I enjoy painting, photography, table tennis, piano, and classical music.

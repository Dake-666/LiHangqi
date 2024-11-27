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


Hi! My name is Hangqi Li (李航奇), a senior undergraduate majoring in Computer Science & Technology at [Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/), [Zhejiang University](https://www.zju.edu.cn/english/). I currently hold a GPA of 3.93/4.0, ranking top 2% among 301 students, and expect to receive my degree in June, 2025.

I am broadly interested in Applied Machine Learning, Controllable Generative Models and AI for Common Good. I have been doing research engaged in AI4Science to apply CV and NLP techniques to address real-world problems, as an intern advised by [Prof. Fei Wu](https://scholar.google.com/citations?user=XJLn4MYAAAAJ&hl=en) at [Zhejiang University](https://www.zju.edu.cn/english/) Digital Media Computing and Design (DCD) Lab. I'm now a research intern with [Prof. Zeyu Zheng](https://zheng.ieor.berkeley.edu/) at [UC Berkeley](https://ieor.berkeley.edu/) Department of Industrial Engineering and Operations Research (IEOR), focusing on controllable generation of structured data such as music and images.


# 📖 Educations
- *2021.09 - Present* B.E. in Computer Science and Technology, Zhejiang University, Hangzhou, China
  <!-- - *Minor:* Advanced Honor Class of Engineering Education Program (Honors program of Zhejiang University) -->


# 🔥 News
- Working on a project focusing on image generation advised by [Prof. Zeyu Zheng](https://zheng.ieor.berkeley.edu/) at UC Berkeley.


# 📝 Publications and Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/iclcr25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UniComposer: Band-Level Music Composition with Symbolic and Audio Unification**

**Hangqi Li**, [Zeyu Zheng](https://zheng.ieor.berkeley.edu/)

***Under Review***


[[Paper]](https://openreview.net/pdf?id=FOcleL0ltt), [[Project Page]](https://sites.google.com/view/unicomposer)


- *UniComposer*: the first band-level music generation system that involves collaborative roles of instruments, tailored to harmonize, provide rhythm, with careful selection of instruments to match the melody's expressive qualities, through cascaded bar-based diffusion models.
- An approach that integrates the advantages of both symbolic and audio music, using separate encoders and a shared decoder to bridge both formats within a common feature space, while gaining computational efficiency as well.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/eccv24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LLMCO4MR: LLMs-aided Neural Combinatorial Optimization for Ancient Manuscript Restoration from Fragments with Case Studies on Dunhuang**

[Yuqing Zhang](https://www.linkedin.com/in/yuqingzhang12/), **Hangqi Li**, [Shengyu Zhang](https://shengyuzhang.github.io/), [Runzhong Wang](https://runzhong.wang/), [Baoyi He](https://www.researchgate.net/profile/Baoyi-He), [Huaiyong Dou](https://person.zju.edu.cn/douhyong), [Junchi Yan](https://thinklab.sjtu.edu.cn/), [Yongquan Zhang](https://rwsk.zju.edu.cn/rwsken/2019/0611/c30365a1224122/page.htm), and [Fei Wu](https://scholar.google.com/citations?user=XJLn4MYAAAAJ&hl=en)

***ECCV 2024***


[[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-73226-3_15)


- Formulate the fragment selection subtask for manuscript restoration as a combinatorial optimization (CO) problem, and introduce *LLMCO4MR*, a LLMs-aided Neural Combinatorial Optimization solver.
- The first to restore the manuscript from a subset of fragments with *outliers*, and introduce MLLMs for manuscript recovery and jigsaw puzzle-like tasks. We carry assembly on Dunhuang manuscripts, Dead Sea papyrus, and Chinese oracle bone fragments.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/emnlp24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PhiloGPT: A Philology-Oriented Large Language Model for Ancient Chinese Manuscripts with Dunhuang as Case Study**

[Yuqing Zhang](https://www.linkedin.com/in/yuqingzhang12/), [Baoyi He](https://www.researchgate.net/profile/Baoyi-He), [Yihan Chen](https://www.linkedin.com/in/yihanrosechen/), **Hangqi Li**, [Yue Han](zjhanyue@zju.edu.cn), [Shengyu Zhang](https://shengyuzhang.github.io/), [Huaiyong Dou](https://person.zju.edu.cn/douhyong), [Junchi Yan](https://thinklab.sjtu.edu.cn/), [Zemin Liu](https://zemin-liu.github.io/), [Yongquan Zhang](https://rwsk.zju.edu.cn/rwsken/2019/0611/c30365a1224122/page.htm), [Fei Wu](https://scholar.google.com/citations?user=XJLn4MYAAAAJ&hl=en)

***EMNLP 2024***

[[Paper]](https://aclanthology.org/2024.emnlp-main.163/)

- *PhiloCorpus-ZH*, a collection of ancient Chinese manuscripts; and *PhiloBenchmark* including 9 tasks to assess the performance of ancient Chinese LLMs for manuscript discoveries.
- *PhiloCoP*, a framework that adheres to chain-of-thoughts for philologists navigating vocabulary and grammatical phenomena in classical Chinese. *PhiloGPT* has been applied to tasks including the restoration and distinction of Dunhuang manuscripts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM Asia 2024</div><img src='images/mmasia24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DHelper: A Collaborative Toolkit for Manuscript Restoration**

[Yue Han](zjhanyue@zju.edu.cn), [Shuanghe Zhu](3220100501@zju.edu.cn), [Yuqing Zhang](https://www.linkedin.com/in/yuqingzhang12/), **Hangqi Li**, [Baoyi He](https://www.researchgate.net/profile/Baoyi-He), [Shengyu Zhang](https://shengyuzhang.github.io/), [Huaiyong Dou](https://person.zju.edu.cn/douhyong), [Junchi Yan](https://thinklab.sjtu.edu.cn/), [Zemin Liu](https://zemin-liu.github.io/), [Yongquan Zhang](https://rwsk.zju.edu.cn/rwsken/2019/0611/c30365a1224122/page.htm), [Fei Wu](https://scholar.google.com/citations?user=XJLn4MYAAAAJ&hl=en)
<!-- ( * equal contribution) -->

***ACM MM Asia 2024*** 

[[Paper]](https://aclanthology.org/2024.emnlp-main.163/)

- The first comprehensive dataset featuring 781 groups of conjugated Dunhuang fragments, with a multi-functional toolkit that facilitates collaboration between large and small models.
- A domain-specific large language model based on the Dunhuang corpus, capable of addressing expert inquiries and introducing knowledge about Dunhuang to the general public.
</div>
</div>


# 📝 Patents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CN Patent</div><img src='images/patent1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-mode Dunhuang residual scroll conjugation method based on text matching and twin network**

**LI HANGQI**; ZHANG YUQING; WU KEYUE; DOU HUAIYONG; YAN JUNCHI; ZHANG SHENGYU; ZHANG YONGQUAN

***CN117953504A, Pending*** 

[[Patent]](https://worldwide.espacenet.com/patent/search/family/090792079/publication/CN117953504A?q=117953504)

- A multi-mode Dunhuang scroll conjugation method using text matching, a twin network, and OCR to extract masks, pair images, and calculate candidate positions.
- Multi-modal text and contour matching enhance accuracy, and global splicing employs image search techniques. This method applies to Dunhuang scroll conjugation and advances research in ancient linguistics and social studies.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CN Patent</div><img src='images/patent2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Combinatorial optimization and multi-modal large model-based conjugates Dunhuang fragment screening method**

**LI HANGQI**; ZHANG YUQING; WU KEYUE; DOU HUAIYONG; YAN JUNCHI; ZHANG SHENGYU; ZHANG YONGQUAN

***CN118570540A, Pending*** 

[[Patent]](https://worldwide.espacenet.com/patent/search/family/092463231/publication/CN118570540A?q=118570540)

- A method for screening Dunhuang fragments using combinatorial optimization and a multi-modal model, involving feature extraction, matching score prediction, and graph formation for high-scoring fragments.
- A graph neural network identifies splicable fragments, while a multi-modal model checks for errors using cue words. Error fragments are removed, and re-screening generates new candidate sets.
</div>
</div>

# 🎖 Honors and Awards

- *2023 - 2024* Zhejiang Provincial Government Scholarship 
  
  Awarded for academic and innovative outstanding in Zhejiang Province, top 5%

- *2021 - 2022, 2022 - 2023, 2023 - 2024* Zhejiang University Scholarship
  
  Awarded for academic and innovative outstanding, top 3%

- *2022 - 2023, 2023 - 2024*  Chu Kochen Honors College Scholarship
  
  Awarded for leading achievements and innovation in the college


<!-- # 🗒 Teaching
# 💬 💻Invited Talks -->

# 🎉 Activities

- *2022 - 2023, 2023 - 2024* Lecturer, Chu Kochen Honors College Peer Academic Assistance Program
  
- *2023.10* Volunteer, Hangzhou 2022 Asian Games
  
- *2022 - 2023* Team Leader, Zhejiang University Peer Mentionship Freshman Assistance Program

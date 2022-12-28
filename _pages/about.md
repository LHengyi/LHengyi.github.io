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

I'm currently working as a researcher in Huawei. I received the Ph.D. degree in Computer Engineering from Northwestern University, United States in 2021, advised by [Prof. Qi Zhu](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/zhu-qi.html), and bachelor degree in Microelectronics from University of Electronic Science and Technology of China in 2016.

My research interests include sensor-fusion based indoor localization, autonmous driving and Cyber-Physical Systems. Many of my PhD works have been published in top design automation conferences, including DAC, ICCAD, ICCD. <a href='https://scholar.google.com/citations?user=MgfmJe8AAAAJ'>Check out my google scholar here.<strong><span id='total_cit'></span></strong></a> 
<!-- (<a href='https://scholar.google.com/citations?user=MgfmJe8AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2022.10*: &nbsp;🎉🎉 Our team ranked 2nd place in the Indoor Positioning and Indoor Navigation (IPIN) Competition, keep working!
- *2022.07*: &nbsp;🎉🎉 We have conducted field tests for our 5G-Inertial Indoor Positioning System, [video](https://www.youtube.com/watch?v=srJXKtUtW_4) (courtesy to [Han Wang](https://wanghan.pro/)).
- *2021.03* &nbsp;🎉🎉 Our work has been awarded as the Best Short Paper in Automotive and Autonomous Vehicle Security Workshop.

# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IV 2021</div><img src='images/IV_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[End-to-end Uncertainty-based Mitigation of Adversarial Attacks to Automated Lane Centering](https://ieeexplore.ieee.org/document/9575549)

Ruochen Jiao<sup>*</sup>, **Hengyi Liang**<sup>*</sup>, Takami Sato, Junjie Shen, Qi Alfred Chen, Qi Zhu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=MgfmJe8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=MgfmJe8AAAAJ:roLk4NBRz8UC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- analyzed the impact of dirty road patch attack across the ADAS pipeline, and developed a method to quantitatively measure the perception uncertainty under attack.
- conducted experiments on both public dataset and LGSVL. The results demonstrate that our approach can significantly improve the system robustness over the original OpenPilot implementation under adversarial attacks, reducing lateral deviation by 55% ~ 90%.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCD 2019</div><img src='images/ICCD_2019.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Security-Driven Codesign with Weakly-Hard Constraints for Real-Time Embedded Systems](https://ieeexplore.ieee.org/abstract/document/8988730)

**Hengyi Liang**, Zhilu Wang, Ruochen Jiao, Qi Zhu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=MgfmJe8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=MgfmJe8AAAAJ:roLk4NBRz8UC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Incorporate weakly-hard constraints on resource-stringent distributed systems, conduct control analysis and schedulability analysis that account for task deadline misses. Develop meta-heuristic multi-objective optimization algorithm to improve system security, fault-tolerance and control performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NOCS 2017</div><img src='images/NOCS_2017.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Addressing Extensibility and Fault Tolerance in CAN-based Automotive Systems](https://ieeexplore.ieee.org/abstract/document/8368590/)

**Hengyi Liang**, Zhilu Wang, Bowen Zheng, Qi Zhu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=MgfmJe8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=MgfmJe8AAAAJ:roLk4NBRz8UC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Identify the metrics for measuring extensibility, fault tolerance and latency that can be captured by the model-based design (MBD) paradigm; present a simulated annealing based algorithm to search the design space, e.g. task allocation and scheduling, and analyze their trade-offs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SMARTCOMP 2017</div><img src='images/SMARTCOMP_2017
.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Delay-aware design, analysis and verification of intelligent intersection management](https://ieeexplore.ieee.org/abstract/document/7946999)

Bowen Zheng, Chung-Wei Lin, **Hengyi Liang**, Shinichi Shiraishi, Wenchao Li, Qi Zhu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=MgfmJe8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=MgfmJe8AAAAJ:roLk4NBRz8UC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Develop a delay-tolerant protocol for intelligent intersection management that can ensure liveness under bounded commnucation delay.
- Model and implement our protocol in the SUMO traffic simulation suite with the extension of modeling communication delays.
- Verify the safety and liveness properties of our protocol by building more abstract timed automata models and leveraging UPPAAL verification tool.
</div>
</div>



# 🎖 Honors and Awards
- Second Place of the Indoor Positioning and Indoor Navigation (IPIN) Competition, 2022. 
- Best Short Paper Award, Automotive and Autonomous Vehicle Security Workshop, 2021.
- 53rd DAC Richard Newton Young Fellowship Award, 2016.
- Meritorious Winner of Mathematical Contest in Modeling, 2014.
- National Inspirational Scholarship, 2013,2014.

# 📖 Teaching Experience
- Teaching assistant, Modeling and Synthesis of Cyber-Physical Systems (EECS 495/395), Northwestern University, Winter 2019.
- Teaching assistant, Engineering Analysis 1 (GEN\_GEN 205-1), Northwestern University, Fall 2019.

# 📖 Educations
- 2018~2021 Ph.D, Computer Engineering, Northwestern University.
- 2015~2017, Ph.D candidate, University of California, Riverside.
- 2011~2015, Bachelor, Microelectronics, University of Electronic Science and Technology of China. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2019.06 - 2019.09*, Mathworks, Natick, U.S.
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

<div style="text-align: justify;">

  <p><span aria-hidden="true"></span> Hi, there!</p>

  <p>Welcome to <strong>Md. Mahmudul Hasan</strong>'s website! I am a senior undergraduate student in <strong>Computer Science and Engineering</strong> at the <strong>University of Dhaka</strong>, where I have focused on developing a strong foundation in both theoretical and applied principles.</p>

  <p>I am deeply interested in the recent advancements of <strong>Artificial Intelligence</strong>, which have led me to pursue research in this field. Currently, I work as an <strong>Undergraduate Research Assistant</strong> at the <strong>Cognitive Agents and Interaction Lab (CAIL)</strong> under the supervision of <a href="https://mmkhansajeeb.com/" target="_blank" rel="noopener">Dr. Md. Mosaddek Khan</a>. My research interests broadly include:</p>

  <!-- Visual echo of your interests (kept your original sentence above untouched) -->
  <ul style="margin: 0.5rem 0 1rem 1.2rem;">
    <li><strong>Machine Learning (ML)</strong></li>
    <li><strong>Large Language Models (LLMs)</strong></li>
    <li><strong>Vision-Language Models (VLMs)</strong></li>
    <li><strong>Multimodal Learning</strong></li>
  </ul>

  <p>Beyond research, I have a strong passion for <strong>algorithmic problem solving</strong> and devoted much of my early undergraduate years to <strong>competitive programming</strong>. I have also aimed to build a solid understanding of <strong>software engineering</strong> through various academic projects.</p>

  <p>Looking ahead, I hope to engage in <strong>innovative research projects</strong> that challenge my abilities and allow me to contribute meaningfully to the field.</p>

  <div style="background-color:rgb(236, 236, 236); padding: 10px; border-left: 5px solid rgb(2, 47, 92); margin-top: 15px; margin-bottom: 15px;">
        <span style="color:rgb(34, 75, 141)"><strong>
        I'm expected to graduate before Jan 2026 and am currently on the job market (for both academic and industrial opportunities). 
        I would greatly appreciate it if you could email me about any available opportunities!
        </strong>
        </span>
    </div>

</div>

# News

<!-- - _2022.02_: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2022.02_: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

- *Sep 2025*: Our paper **GraDeT-HTR** is accepted at **EMNLP 2025** System Demonstrations! Check out the [paper](https://arxiv.org/abs/2509.18081) and [code](https://github.com/mahmudulyeamim/GraDeT-HTR).

- *Jun 2025*: We’ve released our new work **GraDeT-HTR**, now freely available for public use!  Visit our [site](https://cognistorm.ai/hcr).


# Publications

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Demo</div><img src='images/papers/GraDeT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**GraDeT-HTR: A Resource-Efficient Bengali Handwritten Text Recognition System utilizing Grapheme-based Tokenizer and Decoder-only Transformer**](https://arxiv.org/abs/2509.18081) 

**Md. Mahmudul Hasan**, Ahmed Nesar Tahsin Choudhury, Mahmudul Hasan, Md. Mosaddek Khan

- Utilizes a decoder-only architecture for Bengali handwritten text recognition without any pretrained LM.
- Employs a grapheme-based tokenizer, which significantly boosts recognition accuracy.

<div style="display: inline">
    <a href="https://arxiv.org/abs/2509.18081"> <strong>[paper]</strong></a>
    <a href="https://github.com/mahmudulyeamim/GraDeT-HTR"> <strong>[code]</strong></a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()" ><strong>[abstract]</strong></a>
    <div class="abstract"  style="overflow: hidden; display: none;">  
        <p> Despite Bengali being the sixth most spoken language in the world, handwritten text recognition (HTR) systems for Bengali remain severely underdeveloped. The complexity of Bengali script--featuring conjuncts, diacritics, and highly variable handwriting styles--combined with a scarcity of annotated datasets makes this task particularly challenging. We present GraDeT-HTR, a resource-efficient Bengali handwritten text recognition system based on a Grapheme-aware Decoder-only Transformer architecture. To address the unique challenges of Bengali script, we augment the performance of a decoder-only transformer by integrating a grapheme-based tokenizer and demonstrate that it significantly improves recognition accuracy compared to conventional subword tokenizers. Our model is pretrained on large-scale synthetic data and fine-tuned on real human-annotated samples, achieving state-of-the-art performance on multiple benchmark datasets. </p>
    </div>
</div>

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards

- _2023 Mar_: 54th out of 158 teams in the ICPC Asia Dhaka Regional Onsite Contest
- _2023 Feb_: 32nd out of 1477 teamsn in the ICPC Asia Dhaka Regional Site Online Preliminary Contest -->

# Educations

- *2022 – 2026* (expected)  
  **B.Sc. in Computer Science & Engineering**, *University of Dhaka*

<!-- # 💬 Invited Talks

- _2021.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2021.03_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships

- _2019.05 - 2020.02_, [Lorem](https://github.com/), China. -->

# Research Experience

- *Jan 2024 – Present*  
    **Undergraduate Research Assistant**  
    Cognitive Agents and Interaction Lab (CAIL), *University of Dhaka*  
    Working under the supervision of [Dr. Md. Mosaddek Khan](https://mmkhansajeeb.com/)

# Teaching Experience

- *Jan 2022 – Jun 2023*  
  **Physics Instructor**  
  [Udvash-উদ্ভাস](https://udvash.com/HomePage), *Dhaka, Bangladesh*  
  Taught Physics to high school students (Grades 9–12)


<!-- # 🎖 Honors and Awards

- _2023 Mar_: **54th** out of 158 teams in the **ICPC Asia Dhaka Regional** Onsite Contest
- _2023 Feb_: **32nd** out of 1477 teams in the **ICPC Asia Dhaka Regional Preliminary** Online Contest -->

<!-- # Projects

- *Oct 2024 – Jan 2025*, **[Flash: Fastest-Way-to-Learn](https://github.com/saged-sama/Flash---Fastest-Way-to-Learn)**  
  Built an end-to-end **video summarization system** using **multimodal deep learning**.  
  Developed a fully functional **course-selling platform** with **Spring Boot**, **Next.js**, and **PyTorch**.

- *Apr 2024*, **[ConvoCorner](https://github.com/mahmudulyeamim/ConvoCorner)**  
  Designed a **real-time messaging app** with text and image support using **WebSockets**.  
  Implemented the **TCP/IP protocol** from scratch to ensure reliable data transmission.

- *Sep 2023 – Nov 2023*, **[KodeShell](https://github.com/mahmudulyeamim/KodeShell)**  
  Created an **Android app** for aggregating **contest schedules** and **user statistics** across competitive programming platforms.  
  Added **community features** such as posts, user search, and messaging.

- *Feb 2023 – May 2023*, **[SmartAcademicManager](https://github.com/mahmudulyeamim/SmartAcademicManager)**  
  Developed a **desktop application** for managing academic resources, schedules, tasks, and course attendance.  
  Designed a **modern JavaFX interface** for streamlined academic management.

- *Oct 2022 – Dec 2022*, **[Cannon Fight](https://github.com/mahmudulyeamim/Cannon-Fight)**  
  Built a **2D projectile-based shooting game** in **C/C++** using **SDL2**, featuring both **single-player** and **multiplayer** modes. -->

# Projects

- *Oct 2024 – Jan 2025*, **[Flash: Fastest-Way-to-Learn](https://github.com/saged-sama/Flash---Fastest-Way-to-Learn)**  
  Built an end-to-end **video summarization system** using **multimodal deep learning**.  
  Developed a fully functional **course-selling platform** with **Spring Boot**, **Next.js**, and **PyTorch**.

- *Apr 2024*, **[ConvoCorner](https://github.com/mahmudulyeamim/ConvoCorner)**  
  Designed a **real-time messaging app** with text and image support using **WebSockets**.  
  Implemented the **TCP/IP protocol** from scratch to ensure reliable data transmission.

- *Sep 2023 – Nov 2023*, **[KodeShell](https://github.com/mahmudulyeamim/KodeShell)**  
  Created an **Android app** for aggregating **contest schedules** and **user statistics** across competitive programming platforms.  
  Added **community features** such as posts, user search, and messaging.

- *Feb 2023 – May 2023*, **[SmartAcademicManager](https://github.com/mahmudulyeamim/SmartAcademicManager)**  
  Developed a **desktop application** for managing academic resources, schedules, tasks, and course attendance.  
  Designed a **modern JavaFX interface** for streamlined academic management.

- *Oct 2022 – Dec 2022*, **[Cannon Fight](https://github.com/mahmudulyeamim/Cannon-Fight)**  
  Built a **2D projectile-based shooting game** in **C/C++** using **SDL2**, featuring both **single-player** and **multiplayer** modes.

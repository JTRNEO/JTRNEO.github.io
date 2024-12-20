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

# 📌 Short Bio (<a href="CV/songjian.pdf">**CV**)
Jian Song is currently a Ph.D student at [Machine Learning and Statistical Data Analysis Lab](https://www.ms.k.u-tokyo.ac.jp/), [The University of Tokyo](https://www.u-tokyo.ac.jp/en/), advised by [Prof. Naoto Yokoya](https://naotoyokoya.com/). He is also a research Part-timer of the [Geoinformatics Team](https://geoinformatics2018.com/) at the [RIKEN AIP](https://aip.riken.jp/). 

His research centers on creating and utilizing high-fidelity synthetic 3D environments to address real-world remote sensing challenges. By combining advanced scene generation and transfer learning techniques, he aims to unlock scalable global 3D understanding for applications in urban planning, environmental monitoring, and beyond. 

He is a big fan of Dota2 and Mahjong.

# 🔥 News
- *2024.11*: &nbsp;🎉🎉 ChangeMamba has been selected as <b>ESI Hot Paper</b>! 
- *2024.11*: &nbsp;🎉🎉 Our paper in generalized few-shot semantic segmentation has been accepted by <b>IEEE GRSL</b> (<a href="https://ieeexplore.ieee.org/document/10741284/" target="_blank">link</a>)!
- *2024.10*: &nbsp;🎉🎉 One paper in 3D semantic understanding using monocular EO data has been accepted by <b>NeurIPS 2024 Spotlight</b> (<a href="https://jtrneo.github.io/SynRS3D/" target="_blank">link</a>)! 
- *2024.06*: &nbsp;🎉🎉 One co-authored paper has been accepted by <b>IEEE TGRS</b> (<a href="https://ieeexplore.ieee.org/document/10565926" target="_blank">link</a>)!

# 📜 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">NeurIPS 2024</div>
      <div class="badge spotlight-badge">Spotlight</div>
    </div>
    <img src='images/SynRS3D.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [SynRS3D: A Synthetic Dataset for Global 3D Semantic Understanding from Monocular Remote Sensing Imagery](https://arxiv.org/abs/2406.18151)

  **Jian Song**, Hongruixuan Chen, Weihao Xuan, Junshi Xia, Naoto Yokoya

  In <em>Proc. 38th Annual Conference on Neural Information Processing Systems (Datasets and Benchmarks Track), 2024.</em> 
  <span style="color: #ff4500; font-weight: bold;">*Spotlight Paper* [top 3.08%]</span>

  <div class="paper-links">
    <a class="paper-link" href="https://jtrneo.github.io/SynRS3D/" title="Project Page">
      <i class="fas fa-home"></i> Project Page
    </a>
    <a class="paper-link" href="https://arxiv.org/abs/2406.18151" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/JTRNEO/SynRS3D" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
    <a class="paper-link" href="https://zenodo.org/records/13905264" title="Data">
      <i class="fas fa-database"></i> Data
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">TGRS 2024</div>
      <div class="badge spotlight-badge">ESI Hot Paper / ESI Highly Cited Paper</div>
    </div>
    <img src='images/ChangeMamba.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space Model](https://ieeexplore.ieee.org/document/10565926)

  Hongruixuan Chen<span>*</span>, <strong>Jian Song<span>*</span></strong>, Chengxi Han, Junshi Xia, Naoto Yokoya

  <em>IEEE Transactions on Geoscience and Remote Sensing (**TGRS**), 2024.</em> 
  <span style="color: #ff4500; font-weight: bold;">*ESI Hot Paper / ESI Highly Cited Paper*</span>

  <div class="paper-links">
    <a class="paper-link" href="https://ieeexplore.ieee.org/document/10565926" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/ChenHongruixuan/MambaCD" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">WACV 2024</div>
    </div>
    <img src='images/SyntheWorld.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [SyntheWorld: A Large-Scale Synthetic Dataset for Land Cover Mapping and Building Change Detection](https://openaccess.thecvf.com/content/WACV2024/html/Song_SyntheWorld_A_Large-Scale_Synthetic_Dataset_for_Land_Cover_Mapping_and_WACV_2024_paper.html)

  **Jian Song**, Hongruixuan Chen, Naoto Yokoya

  In <em>Proc. IEEE/CVF Winter Conference on Applications of Computer Vision, 2024.</em> 

  <div class="paper-links">
    <a class="paper-link" href="https://openaccess.thecvf.com/content/WACV2024/html/Song_SyntheWorld_A_Large-Scale_Synthetic_Dataset_for_Land_Cover_Mapping_and_WACV_2024_paper.html" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/JTRNEO/SyntheWorld" title="Data">
      <i class="fas fa-database"></i> Data
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">ISPRS 2024</div>
    </div>
    <img src='images/exchange.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [Exchange Means Change: An Unsupervised Single-Temporal Change Detection Framework Based on Intra- and Inter-Image Patch Exchange](https://www.sciencedirect.com/science/article/abs/pii/S092427162300309X)

  Hongruixuan Chen, **Jian Song**, Chen Wu, Bo Du, Naoto Yokoya

  <em>ISPRS Journal of Photogrammetry and Remote Sensing, 2023.</em> 

  <div class="paper-links">
    <a class="paper-link" href="https://www.sciencedirect.com/science/article/abs/pii/S092427162300309X" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/ChenHongruixuan/I3PE" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
  </div>
  </div>
</div>

<!-- Journal Articles -->
- [Generalized Few-Shot Semantic Segmentation in Remote Sensing: Challenge and Benchmark](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8859), C. Broni-Bediako, J. Xia, **J. Song**, H. Chen, M. Siam, N. Yokoya, ***IEEE GRSL 2024***

- [ObjFormer: Learning Land-Cover Changes From Paired OSM Data and Optical High-Resolution Imagery via Object-Guided Transformer](https://ieeexplore.ieee.org/document/10551264), H. Chen, C. Lan, **J. Song**, C. Broni-Bediako, J. Xia, N. Yokoya, ***IEEE TGRS 2024***

- [Deep Learning for Multi-Label Classification of Coral Conditions in the Indo-Pacific via Underwater Photogrammetry](https://onlinelibrary.wiley.com/doi/10.1002/aqc.4241), X. Shao, H. Chen, K. Magson, J. Wang, **J. Song**, J. Chen, J. Sasaki, ***Aquatic Conservation 2024***

<!-- Conference Papers -->
- [OpenEarthMap Benchmark Suite and Its Applications](https://ieeexplore.ieee.org/abstract/document/10640801), N. Yokoya, J. Xia, C. Broni-Bediako, **J. Song**, H. Chen, ***IGARSS 2024*** (Oral Presentation)

- [Change Detection Between Optical Remote Sensing Imagery and Map Data via Segment Anything Model (SAM)](https://ieeexplore.ieee.org/document/10642789), H. Chen, **J. Song**, N. Yokoya, ***IGARSS 2024*** (Oral Presentation)

- [Disaster Detection from SAR Images with Different Off-Nadir Angles Using Unsupervised Image Translation](https://ceur-ws.org/Vol-3207/paper3.pdf), **J. Song**, B. Adriano, N. Yokoya, ***CDCEO Workshop at IJCAI 2022***


<!-- Education Section
<h2>🎓 Education</h2>
<ul>
  <li>
    <strong>The University of Tokyo, Chiba, Japan</strong>  
    <br><em>Oct. 2021 – Present</em>  
    Ph.D. Candidate in Engineering (Major: Complexity Science and Engineering)  
    <br>Research Topic: Synthetic data-driven 3D semantic reconstruction in remote sensing
  </li>
  <li>
    <strong>Waseda University, Fukuoka, Japan</strong>  
    <br><em>Oct. 2019 – Mar. 2021</em>  
    Master of Engineering (Major: Information Engineering)  
    <br>Research Topic: Flow-guided video object detection
  </li>
  <li>
    <strong>Wuhan University, Wuhan, China</strong>  
    <br><em>Sep. 2018 – Jun. 2021</em>  
    Master of Engineering (Major: Software Engineering)  
    <br>Research Topic: Remote sensing image semantic segmentation
  </li>
  <li>
    <strong>Fujian Agriculture and Forestry University, Fuzhou, China</strong>  
    <br><em>Sep. 2011 – Jun. 2015</em>  
    Bachelor of Agriculture (Major: Forestry Information Engineering)
  </li>
</ul> -->

<!-- Employment History
<h2>💼 Employment History</h2>
<ul>
  <li>
    <strong>The University of Tokyo, Tokyo, Japan</strong>  
    <br><em>Oct. 2021 – May 2024</em>  
    Research Assistant  
    <br>Supervisor: Prof. Naoto Yokoya
  </li>
  <li>
    <strong>RIKEN AIP, Tokyo, Japan</strong>  
    <br><em>Apr. 2021 – Present</em>  
    Research Part-timer  
    <br>Supervisor: Prof. Naoto Yokoya
  </li>
  <li>
    <strong>Inception Institute of Artificial Intelligence, Abu Dhabi, UAE</strong>  
    <br><em>Mar. 2019 – Aug. 2019</em>  
    Research Intern  
    <br>Supervisor: Dr. Fan Zhu
  </li>
  <li>
    <strong>Land Satellite Remote Sensing Application Center, Beijing, China</strong>  
    <br><em>May 2018 – Sep. 2018</em>  
    Research Intern  
    <br>Supervisor: Dr. Yuhang Gan
  </li>
</ul> -->

<!-- Honors and Awards -->
# 🎖 Honors and Awards
<ul>
  <li><em>Dec. 2023</em> AY2024 AI Center Fusion Research Promotion Fund (1,600,000 JPY)</li>
  <li><em>Jul. 2024</em> SPRING GX Self-directed and Integrated Project Research (250,000 JPY)</li>
  <li><em>Apr. 2024</em> SPRING GX Fellowship (180,000 JPY per month)</li>
  <li><em>Dec. 2023</em> AY2023 AI Center Fusion Research Promotion Fund (2,000,000 JPY)</li>
  <li><em>Mar. 2023</em> AY2023 GSFS Challenging New Area Doctoral Research Grant (GSFS Challenge Fund) (600,000 JPY)</li>
  <li><em>Feb. 2020</em> AY2020 JEES–SoftBank AI Scholarship (1,000,000 JPY)</li>
  <li><em>Sep. 2019</em> Kitakyushu Science and Research Park Scholarship (300,000 JPY)</li>
</ul>

<!-- Academic Services -->
# 🛠 Academic Services
<ul>
  <li>Reviewer: IEEE Transactions on Geoscience and Remote Sensing (TGRS)</li>
  <li>Reviewer: ISPRS Journal of Photogrammetry and Remote Sensing</li>
  <li>Reviewer: IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)</li>
  <li>Reviewer: IEEE Access</li>
  <li>Co-organizer: OpenEarthMap Land Cover Mapping Few-Shot Challenge at L3D-IVU CVPR 2024 Workshop 
    <a href="https://cliffbb.github.io/OEM-Fewshot-Challenge/">[Link]</a>
  </li>
</ul>

<!-- Content Section -->
<p style="text-align: center;">
  <div id="clustrmaps-widget" style="max-width: 20%; margin: 0 auto;">
    <script 
      type="text/javascript" 
      id="clustrmaps" 
      src="//clustrmaps.com/map_v2.js?d=uTY2AY6y6-cxWrNfdFwh2S1zspQywC0Y_DfDGQVQclc&cl=ffffff&w=a" 
      async>
    </script>
    <noscript>
      <a href="https://clustrmaps.com/site/1bj1k" title="Visitor Map">
        <img 
          src="//clustrmaps.com/map_v2.png?d=uTY2AY6y6-cxWrNfdFwh2S1zspQywC0Y_DfDGQVQclc&cl=ffffff&w=a" 
          alt="Visitor Map" 
          style="max-width: 20%; height: auto;">
      </a>
    </noscript>
  </div>
  <p style="text-align:center;">
    &copy; Jian Song | Last updated: Dec 8, 2024
  </p>     
</p>

<!-- Footer -->
<footer class="footer" style="text-align: center;">
  <div class="container">
    <div class="content has-text-centered">
      <p style="color: #4A4A4A;">
        This website template is borrowed from 
        <a href="https://github.com/RayeRen/acad-homepage.github.io" style="color: #3273DC;">AcadHomepage</a>
      </p>
    </div>
  </div>
</footer>


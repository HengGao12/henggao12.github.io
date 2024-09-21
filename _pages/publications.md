---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<style>
        a.blue-text {
        color: #87CEEB;
    }
</style>

<a>*</a> indicates co-first authour  
<a>**</a> indicates revised and submitted to other conferences

<ul>

<li>
<p><b>Knowledge Distillation from 3D to Bird’s-Eye-View for LiDAR Semantic Segmentation</b>
<br />Feng Jiang, Heng Gao, Shoumeng Qiu, Haiqiang Zhang, Ru Wan and Jian Pu<sup><a title='Corresponding author'>✉</a></sup>
<br /> IEEE International Conference on Multimedia and Expo (<strong>ICME</strong>), 2022. <br /> 
<a href="https://ieeexplore.ieee.org/abstract/document/10220057" class="blue-text">Link</a> |
<a href="https://arxiv.org/pdf/2304.11393" class="blue-text">Paper</a> |
<a href="https://github.com/fengjiang5/Knowledge-Distillation-from-Cylinder3D-to-PolarNet" class="blue-text">Code</a> |

</p>
</li>
</ul>

# Preprints

<ul>
<li>
<p><b>OAML: Outlier Aware Metric Learning for OOD Detection Enhancement (**)
</b>
<br />Heng Gao*, Zhuolin He*, Shoumeng Qiu, Jian Pu<sup><a title='Corresponding author'>✉</a></sup>
<br /> Technical Report, 2024. <br /> 
<a href="https://arxiv.org/abs/2406.16525" class="blue-text">Paper</a> |
<a href="https://github.com/HengGao12/OAML" class="blue-text">Code</a> |  
  
<ul>
<li>
<p><b>Towards Open-set Camera 3D Object Detection
</b>
<br />Zhuolin He, Xinrun Li, Heng Gao, Jiachen Tang, Shoumeng Qiu, Wenfu Wang, Lvjian Lu, Xiuchong Qiu, Xiangyang Xue, Jian Pu
<br /> Technical Report, 2024. <br /> 
<a href="https://arxiv.org/pdf/2406.17297" class="blue-text">Paper</a> |
<a href="https://github.com/NickHezhuolin/OS-Det3D" class="blue-text">Code</a> |
</p>
</li>

</ul>

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=GYUpPI4AAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

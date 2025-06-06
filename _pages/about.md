---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

# About 

## Short biography

I was born in <a href="https://en.wikipedia.org/wiki/Tengchong" _target="_blank">Tengchong (腾冲市)</a>, a beautiful city in southwest China. After graduating from The First Middle School of Tengchong in 2010, I spent ten years studying in Nanjing, China.

I received my B.Sc. degree from the <a href="https://cs.nju.edu.cn/" _target="_blank">Department of Computer Science and Technology</a>, <a href="https://www.nju.edu.cn/" _target="_blank">Nanjing University</a> in 2014. I received my PhD degree from the <a href="https://www.lamda.nju.edu.cn/CH.MainPage.ashx" target="_blan">LAMDA group</a>, <a href="https://cs.nju.edu.cn/" target="_blank">Department of Computer Science and Technology</a>, <a href="https://www.nju.edu.cn/" target="_blank">Nanjing University</a> in 2020, under the supervision of Professor <a href="https://cs.nju.edu.cn/lwj" target="_blank">Wu-Jun Li</a>. PhD thesis: Discrete Hashing Learning [<a href="https://jiangqy.github.io/publications/assert/PHD_thesis.pdf" target="_blank">pdf</a>].

I was an algorithm researcher at HuaWei from 2020 to 2024, as a member of Huawei's top minds project. At Huawei, my work focused on multimodal search (Petal Search) and multimodal large language models (<a href="https://www.huaweicloud.com/product/pangu.html" target="_blank">Pangu MLLM</a>).

I am currently an Associate Professor at <a href="https://cs.njust.edu.cn/" target="_blank">the School of Compute Science and Engineering</a>, <a href="https://www.njust.edu.cn/" target="_blank">Nanjing University of Science and Technology</a>. 
<!-- I am a member of <a href="http://www.njustkmg.cn/" target="_blank">the Knowledge Mining Group</a> which is affiliated with the PCA Lab. -->

## Internship Experience
<div class="rowl1" style="padding-top: 10px;">
1. ByteDance AI Lab (November, 2018~April,2019).
</div>

## Work Experience   
<div class="rowl1" style="padding-top: 10px;">

1. Huawei. September, 2020~June,2024.
2. Nanjing University of Science and Technology. July, 2024~Now.

</div>

## Professional Service   
<div class="rowl1" style="padding-top: 10px;">

1. IEEE, Transactions on Pattern Analysis and Machine Intelligence, <i>TPAMI</i>. Journal Reviewer.
2. IEEE, Transactions on Neural Networks and Learning System, <i>TNNLS</i>. Journal Reviewer.
3. IEEE, Transactions on Image Processing, <i>TIP</i>. Journal Reviewer.
4. IEEE, Transactions on Signal Processing, <i>TSP</i>. Journal Reviewer.
5. IEEE, Transactions on Multimedia, <i>TMM</i>. Journal Reviewer.
6. Frontiers of Computer Science, <i>FCS</i>. Journal Reviewer.
7. ICLR, NeurIPS, ICML, AISTATS, CVPR, AAAI, ACCV. Conference Reviewer.
8. AAAI-2019, AAAI-2020, AAAI-2025. PC member.

</div>


{% if site.data.awards %}
## Awards
<div class="rowl1" style="padding-top: 10px;">

{% for award in site.data.awards %}
{{ forloop.index }}. {{ award.name }}{% if award.name_url %}{% endif %} {% if award.organisation %}. {% if award.organisation_url %}<a href="{{ award.organisation_url }}" target="_blank">{% endif %} {{ award.organisation }}{% if award.organisation_url %}</a>{% endif %}{% endif %}{% if award.subtitle %}: {{ award.subtitle }}{% endif %} ({{ award.year }}).
{% endfor %}
</div>
{% endif %}

<!-- {% if site.data.friends %}
## Friends
<div class="rowl1" style="padding-top: 10px;"> -->

<!-- {% for friend in site.data.friends %}
{{ forloop.index }}. <strong>{{ friend.name }}: </strong>{% if friend.homepage %}<a href="{{ friend.homepage }}" target="_blank">homeage{% endif %}</a>.
{% endfor %}
</div>
{% endif %} -->

---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About 

### Short biography

I was born in <a href="https://en.wikipedia.org/wiki/Tengchong" _target="_blank">Tengchong (腾冲市)</a>, a beautiful city in southwest China. After graduating from The First Middle School of Tengchong in 2010, I spent ten years studying in Nanjing, China.

I received my B.Sc. degree from the <a href="https://cs.nju.edu.cn/" _target="_blank">Department of Computer Science and Technology</a>, <a href="https://www.nju.edu.cn/" _target="_blank">Nanjing University</a> in 2014.

I received my PhD degree from the <a href="https://www.lamda.nju.edu.cn/CH.MainPage.ashx" target="_blan">LAMDA group</a>, <a href="https://cs.nju.edu.cn/" target="_blank">Department of Computer Science and Technology</a>, <a href="https://www.nju.edu.cn/" target="_blank">Nanjing University</a> in 2020, under the supervision of Professor <a href="https://cs.nju.edu.cn/lwj" target="_blank">Wu-Jun Li</a>. PhD thesis: Discrete Hashing Learning [<a href="https://jiangqy.github.io/publications/assert/PHD_thesis.pdf" target="_blank">pdf</a>].

I am currently an algorithm engineer at HuaWei.

### Internship Experience
<div class="rowl1" style="padding-top: 10px;">

1. <strong>ByteDance AI Lab (November, 2018~April,2019).</strong>
</div>

{% if site.data.awards %}
### Awards
<div class="rowl1" style="padding-top: 10px;">

{% for award in site.data.awards %}
{{ forloop.index }}. <strong>{{ award.name }}</strong>{% if award.name_url %}{% endif %} {% if award.organisation %}. {% if award.organisation_url %}<a href="{{ award.organisation_url }}" target="_blank">{% endif %} {{ award.organisation }}{% if award.organisation_url %}</a>{% endif %}{% endif %}{% if award.subtitle %}: {{ award.subtitle }}{% endif %} ({{ award.year }}).
{% endfor %}
</div>
{% endif %}

{% if site.data.friends %}
### Friends
<div class="rowl1" style="padding-top: 10px;">

{% for friend in site.data.friends %}
{{ forloop.index }}. <strong>{{ friend.name }}: </strong>{% if friend.homepage %}<a href="{{ friend.homepage }}" target="_blank">homeage{% endif %}</a>.
{% endfor %}
</div>
{% endif %}

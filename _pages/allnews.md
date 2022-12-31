---
title: "News"
layout: page
sitemap: false
permalink: /allnews.html
---

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>
<br/>
{{ article.content }}
{% endfor %}
</div>

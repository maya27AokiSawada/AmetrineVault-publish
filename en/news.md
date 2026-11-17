---
layout: default
lang: en
title: News
description: News about AmetrineVault.
alt_lang: /news/
permalink: /en/news/
---

# News

The same news is shown in the app's Settings. For what changed in each version, see the [Release Notes]({{ '/en/changelog/' | relative_url }}).

{% for item in site.data.news %}
<article class="entry" id="{{ item.id }}">
  <p class="entry-date"><time datetime="{{ item.date | date: '%Y-%m-%d' }}">{{ item.date | date: '%B %-d, %Y' }}</time></p>
  <h2>{{ item.title.en }}</h2>
  {{ item.body.en | markdownify }}
</article>
{% endfor %}

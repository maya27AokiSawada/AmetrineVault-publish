---
layout: default
lang: ja
title: お知らせ
description: AmetrineVault のお知らせ。
alt_lang: /en/news/
permalink: /news/
---

# お知らせ

アプリの設定画面にも、同じお知らせが表示されます。更新の内容は[変更履歴]({{ '/changelog/' | relative_url }})をご覧ください。

{% for item in site.data.news %}
<article class="entry" id="{{ item.id }}">
  <p class="entry-date"><time datetime="{{ item.date | date: '%Y-%m-%d' }}">{{ item.date | date: '%Y年%-m月%-d日' }}</time></p>
  <h2>{{ item.title.ja }}</h2>
  {{ item.body.ja | markdownify }}
</article>
{% endfor %}

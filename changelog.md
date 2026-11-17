---
layout: default
lang: ja
title: 変更履歴
description: AmetrineVault の各バージョンの変更内容。
alt_lang: /en/changelog/
permalink: /changelog/
---

# 変更履歴

お使いのバージョンは、アプリの「設定」→「このアプリについて」で確認できます。ストアでの公開は OS ごとに日付が前後することがあります。

{% for release in site.data.changelog %}
<article class="entry" id="v{{ release.version }}">
  <h2>{{ release.version }}</h2>
  <p class="entry-date"><time datetime="{{ release.date | date: '%Y-%m-%d' }}">{{ release.date | date: '%Y年%-m月%-d日' }}</time></p>
  <ul>
    {% for note in release.notes.ja %}<li>{{ note }}</li>
    {% endfor %}
  </ul>
</article>
{% endfor %}

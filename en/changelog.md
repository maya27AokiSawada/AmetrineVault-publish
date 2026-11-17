---
layout: default
lang: en
title: Release Notes
description: What changed in each version of AmetrineVault.
alt_lang: /changelog/
permalink: /en/changelog/
---

# Release Notes

You can check your version in the app under Settings → About this app. Release dates may differ slightly between app stores.

{% for release in site.data.changelog %}
<article class="entry" id="v{{ release.version }}">
  <h2>{{ release.version }}</h2>
  <p class="entry-date"><time datetime="{{ release.date | date: '%Y-%m-%d' }}">{{ release.date | date: '%B %-d, %Y' }}</time></p>
  <ul>
    {% for note in release.notes.en %}<li>{{ note }}</li>
    {% endfor %}
  </ul>
</article>
{% endfor %}

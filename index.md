---
layout: default
---

{% capture readme %}{% include_relative README.md %}{% endcapture %}

{% assign lines = readme | split: "\n" %}
{% assign sliced = lines | slice: 1, 9999 %}

{{ sliced | join: "\n" | markdownify }}

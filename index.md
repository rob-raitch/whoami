---
layout: default
---

{% capture readme %}{% include_relative README.md %}{% endcapture %}

{{ readme | split: "\n" | slice: 1, 9999 | join: "\n" }}

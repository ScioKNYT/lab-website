---
layout: default
title: Debug Page
---

# Debug Info

- site.url: `{{ site.url }}`
- site.baseurl: `{{ site.baseurl }}`
- page.url: `{{ page.url }}`
- relative_url: `{{ page.url | relative_url }}`
- absolute_url: `{{ page.url | absolute_url }}`

## Styles Check
{% assign styles = site.pages | where_exp: "file", "file.url contains '/_styles'" %}
Found {{ styles.size }} style files.

<ul>
{% for style in styles %}
  <li>{{ style.path }} -> {{ style.url }} -> {{ style.url | relative_url }}</li>
{% endfor %}
</ul>

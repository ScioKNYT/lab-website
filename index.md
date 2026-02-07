---
layout: default
---

# Welcome to the SMART Lab
### Shape Memory Alloys Research Team

We are using advanced materials to transform aerospace and defence applications.

{% include section.html %}

## Research Areas

**Shape Memory Alloys**
Developing novel alloys with high transformation temperatures.

**Aerospace Applications**
Creating adaptive structures for aircraft wings.

**Defence Systems**
Designing impact-resistant materials for protection.

{% include section.html %}

{% capture text %}
Our Lab works on improving materials for high-performance applications.
We are working on **Characterizing Shape Memory Effect** and **Material Fatigue Analysis**.

{% include button.html link="research" text="See our research" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
{% endcapture %}

{% include feature.html image="images/photo.jpg" link="research" title="Our Research" text=text %}

{% capture text %}
We are a collaborative group of researchers eager to push the frontiers of material science.

{% include button.html link="team" text="Meet our team" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
{% endcapture %}

{% include feature.html image="images/photo.jpg" link="team" title="Our Team" flip=true text=text %}

{% include section.html %}

## News

{% for post in site.posts limit:4 %}
{% include post-excerpt.html
    title=post.title
    date=post.date
    url=post.url
    tags=post.tags
    excerpt=post.excerpt
    style="tiny"
%}
{% endfor %}

[See all news](blog/)

{% include section.html %}

### Tools and Resources
We prioritize open data. Our datasets and code are available on our [GitHub](https://github.com/ScioKNYT) page.

### Joining the OMNI Lab
If you are interested in joining please go to the [Joining the Lab](join/) page.

{% include section.html %}

## Collaborators, Partners & Funding

Our work is supported by:

- **Department of Materials Science**
- **Defence Research Organization**

<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 30px; margin: 40px 0;">
  <!-- Placeholders for logos -->
  <div style="width: 200px; height: 100px; background: #eee; display: flex; align-items: center; justify-content: center;">Logo 1</div>
  <div style="width: 200px; height: 100px; background: #eee; display: flex; align-items: center; justify-content: center;">Logo 2</div>
  <div style="width: 200px; height: 100px; background: #eee; display: flex; align-items: center; justify-content: center;">Logo 3</div>
</div>

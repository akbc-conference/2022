---
title: Accepted Papers
layout: page-fullwidth
permalink: /papers/
header:
  image_fullwidth: "generic-gradient.png"
---

All papers, with their reviews and other details, are also available on [OpenReview](https://openreview.net/group?id=AKBC.ws/2022/Conference).

## Archival Papers

<ul>
{% for paper in site.data.papers %}
    {% if paper['archival_status'] != "" and paper['archival_status'] != "Non-Archival" %}
        {% include paper.html p=paper %}
    {% endif %}
{% endfor %}
</ul>

## Non-Archival Papers

<ul>
{% for paper in site.data.papers %}
    {% if paper['archival_status'] == "" or paper['archival_status'] == "Non-Archival" %}
        {% include paper.html p=paper %}
    {% endif %}
{% endfor %}
</ul>
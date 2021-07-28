---
title: Workshops
layout: page-fullwidth
permalink: /workshops/
header:
  image_fullwidth: "irvine-header.jpg"
---

<h2> Thursday [October 7th] </h2>

<ul>
{% for workshop in site.data.workshops_day1 %}
    <li>
    <b>
        {{- workshop.name -}}
        {% if workshop.acronym %}
            ({{- workshop.acronym -}})
        {%- endif -%}
    </b>, <i>{{- workshop.duration -}}</i>
    {%- if workshop.url -%}
    , <a href="{{ workshop.url }}">Website</a>
    {%- endif -%}
    {%- if workshop.organizers -%}
    <br>
    <i>
        {{- workshop.organizers -}}
    </i>
    {%- endif -%}
    </li>
{% endfor %}
</ul>

<br />
<h2> Friday [October 8th] </h2>

<ul>
{% for workshop in site.data.workshops_day2 %}
    <li>
    <b>
        {{- workshop.name -}}
        {% if workshop.acronym %}
            ({{- workshop.acronym -}})
        {%- endif -%}
    </b>, <i>{{- workshop.duration -}}</i>
    {%- if workshop.url -%}
    , <a href="{{ workshop.url }}">Website</a>
    {%- endif -%}
    {%- if workshop.organizers -%}
    <br>
    <i>
        {{- workshop.organizers -}}
    </i>
    {%- endif -%}
    </li>
{% endfor %}
</ul>

If you have any questions, please get in touch with our workshop chairs.

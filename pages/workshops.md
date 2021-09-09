---
title: Workshops
layout: page-fullwidth
permalink: /workshops/
header:
  image_fullwidth: "generic-gradient.png"
---

<h2> Thursday [October 7th] </h2>

<ul>
{% for workshop in site.data.workshops %}
    {% if workshop.day == 1 %}
    <li>
    <b>
        {{- workshop.name -}}
        {% if workshop.acronym %}
            ({{- workshop.acronym -}})
        {%- endif -%}
    </b>
    {%- if workshop.url -%}
    , <a href="{{ workshop.url }}">Website</a>
    {%- endif -%}
    <br>
    <i>
    {%- for organizer in workshop.organizers -%}
        {{- organizer -}}
        {%- if forloop.last == true -%}
            .
        {%- else -%}
            ,&nbsp;
        {%- endif -%}
    {%- endfor -%}
    </i>
    </li>
    {%- endif -%}
{% endfor %}
</ul>

<br />
<h2> Friday [October 8th] </h2>

<ul>
{% for workshop in site.data.workshops %}
    {% if workshop.day == 1 %}
    <li>
    <b>
        {{- workshop.name -}}
        {% if workshop.acronym %}
            ({{- workshop.acronym -}})
        {%- endif -%}
    </b>
    {%- if workshop.url -%}
    , <a href="{{ workshop.url }}">Website</a>
    {%- endif -%}
    <br>
    <i>
    {%- for organizer in workshop.organizers -%}
        {{- organizer -}}
        {%- if forloop.last == true -%}
            .
        {%- else -%}
            ,&nbsp;
        {%- endif -%}
    {%- endfor -%}
    </i>
    </li>
    {%- endif -%}
{% endfor %}
</ul>

If you have any questions, please get in touch with our workshop chairs.

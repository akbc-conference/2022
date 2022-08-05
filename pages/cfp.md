---
title: Call for Papers
layout: page-fullwidth
order: 0
permalink: /cfp/
header:
  image_fullwidth: "generic-gradient.png"
---

**4th Conference on Automated Knowledge Base Construction (AKBC)**<br>
November 3rd-5th, 2022, Thursday-Saturday (London, UK and online)<br>
Homepage: [http://www.akbc.ws](http://akbc.ws)<br>
Email: [info@akbc.ws](mailto:info@akbc.ws)<br>

### Key dates

- **Paper submission deadline (OpenReview)**: July 10th
- **Commitment deadline (ARR, with reviews and meta review)**: August 5th
- **Author response period**: August 5th - August 10th
- **Notification of acceptance**: September 1st
- **Camera-ready deadline**: September 15th
- **Conference & Workshop Dates**: November 3-5th

All deadlines are 11.59 pm UTC -12h ("anywhere on Earth").

### Knowledge Base Construction

Knowledge gathering, representation, and reasoning are among the fundamental challenges of artificial intelligence. Large-scale repositories of knowledge about entities, relations, and their abstractions are known as “knowledge bases”. Most major technology companies now have substantial efforts in knowledge base construction. Related scholarly work spans many research areas, including machine learning, natural language processing, computer vision, information integration, databases, search, data mining, knowledge representation, human computation, human-computer interfaces, and fairness. The AKBC conference serves as a research forum for gathering all these areas, in both academia and industry.

### Call for Papers

We invite the submission of papers describing previously unpublished research, including new methodology, datasets, evaluations, surveys, reproduced results, negative results, and visionary positions.

Topics of interest include, but are not limited to:

- Natural language processing, information extraction, extraction of entities, relations, and events, semantic parsing, coreference, machine reading, entailment, web mining, multilingual NLP.
- Information integration, entity resolution, schema & ontology alignment, text and structure alignment, federated KBs, Semantic Web.
- Machine learning, supervised, unsupervised, lightly-supervised and distantly-supervised learning, deep learning, symbolic learning, multimodal learning, embeddings of knowledge.
- Search, question-answering, reasoning, knowledge base completion, queries on mixtures of structured and unstructured data; querying under uncertainty.
- Multi-modal knowledge bases: structured data, text, images, video, audio.
- Human-computer interaction, crowdsourcing, interactive learning.
- Fairness, accountability, transparency, misinformation, multiple viewpoints, uncertainty.
- Databases, probabilistic databases, distributed databases, database cleaning, scalable computation, distributed computation, dynamic data, online adaptation of knowledge.
- Systems, languages and toolkits, demonstrations of existing knowledge bases.
- Evaluation of AKBC, datasets, evaluation methodology.

Reviewing will be double-blind on the OpenReview platform, with papers, reviews and comments publicly visible. Papers should be restricted to 10 single-column pages, excluding references. Appendices should be put after references and submitted in one PDF document. We also encourage authors to upload their code and data (<=100 Mb) as part of their supplementary material in order to help reviewers assess the quality of the work. Like submissions, supplementary material must be anonymized.

All submissions must be formatted with LaTeX using the following LaTeX source: You can either download the template [here](https://github.com/akbc-conference/style-files/blob/master/akbc-latex.zip?raw=true) or use the [Overleaf template](https://www.overleaf.com/latex/templates/akbc22-latex/kctstgcbhvsn).

Submission site: [https://openreview.net/group?id=AKBC.ws/2022/Conference](https://openreview.net/group?id=AKBC.ws/2022/Conference).

**Submission of previously published/accepted work**: Submissions that are identical (or substantially similar) to versions that have been previously published, or accepted for publication, are not allowed and violate our dual submission policy. However, papers that cite previous related work by the authors and papers that have appeared on non-peered reviewed websites (like arXiv) or that have been presented at workshops (i.e., venues that do not have publication proceedings) do not violate the policy. The policy is enforced during the whole reviewing process.

**Concurrent Submissions**: Concurrent submissions or commitments to other conferences/workshops including EMNLP 2022 is not allowed.


### Invited Talks
The following are confirmed invited speakers. Most of them will attend the conference in person and some will present virtually.

<div class="row">
<div class="columns">
{% for speaker in site.data.speakers %}
<a href="{{ speaker.url }}">{{ speaker.speaker }}</a>, {{ speaker.institution }}<br>
{% endfor %}
</div>
</div>

### Workshops

In addition to the conference program, we will have a one-day collection of workshops on focused topics.

### Organizers

{% for organizer in site.data.organizers %}

<div class="row">
<div class="small-3 large-3 columns">
{{ organizer.position }}<br>
</div>
<div class="small-9 large-9 columns">
<a href="{{ organizer.url }}">{{ organizer.name }}</a>, {{ organizer.location }}<br>
</div>
</div>
{% endfor %}

### Area Chairs

<div class="row">
<div class="columns">
{% for area-chair in site.data.area-chairs %}
<a href="{{ area-chair.url }}">{{ area-chair.name }}</a>, {{ area-chair.location }}<br>
{% endfor %}
</div>
</div>

<br>
**Questions? Please mail: [info@akbc.ws](info@akbc.ws)**
<br>

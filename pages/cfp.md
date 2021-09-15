---
title: Call for Papers
layout: page-fullwidth
order: 0
permalink: /cfp/
header:
  image_fullwidth: "generic-gradient.png"
---

**3rd Conference on Automated Knowledge Base Construction (AKBC)**<br>
October 4-8, 2021, Monday-Friday (held virtually)<br>
Homepage: [http://www.akbc.ws](http://akbc.ws)<br>
Email: [info@akbc.ws](mailto:info@akbc.ws)<br>

### Key dates

- Paper submission deadline: **June 21, 2021**
- Author response period: July 23-30, 2021
- Notification of acceptance: Aug 18, 2021
- Camera-ready papers due: September 15, 2021
- Conference & workshop dates: Monday-Friday, October 4-8, 2021

All deadlines are 11.59 pm UTC -12h ("anywhere on Earth").

### Knowledge Base Construction

Knowledge gathering, representation, and reasoning are among the fundamental challenges of artificial intelligence.  Large-scale repositories of knowledge about entities, relations, and their abstractions are known as “knowledge bases”.  Most major technology companies now have substantial efforts in knowledge base construction. Related scholarly work spans many research areas, including machine learning, natural language processing, computer vision, information integration, databases, search, data mining, knowledge representation, human computation, human-computer interfaces, and fairness.  The AKBC conference serves as a research forum for gathering all these areas, in both academia and industry.

### About the Conference

Nearly a decade after the first AKBC workshop in Grenoble, France, 2010, AKBC became a conference in 2019. Why a stand-alone conference?
- Long-standing and growing interest in the area.
- We want to grow and connect the community beyond existing individual conference communities, bringing together ML, NLP, DB, IR, KRR, semantics, reasoning, common sense, QA, human computation, dialog, and HCI.
- We want to set our own culture, including reviewing practices, and meeting format.
- Why now?  Growing interest across many areas.  Disconnect among multiple relevant communities.  Growing industry and government interest.  Many of the long-existing conferences have grown uncomfortably large; a new, smaller conference can be more intimate, hospitable, and supportive.

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

Authors of accepted papers will have the option for their conference paper to be archival (with full text in AKBC Proceedings, and be considered for best paper awards) or non-archival (listed in AKBC Conference schedule, with full text in OpenReview, and the flexibility to also submit elsewhere).  Double-blind reviewing will be performed on the OpenReview platform, with papers, reviews and comments publicly visible.

Papers should be restricted to 10 single-column pages, excluding references. Appendices should be put after references and submitted in one PDF document. We also encourage authors to upload their code and data (<=100 Mb) as part of their supplementary material in order to help reviewers assess the quality of the work. Like submissions, supplementary material must be anonymized.

All submissions must be formatted with LaTeX using the following LaTeX source: [akbc-latex.zip](https://github.com/akbc-conference/style-files/blob/master/akbc-latex.zip?raw=true)

Submission site: [https://www.akbc.ws/2021/submission](https://www.akbc.ws/2021/submission).

**Dual Submission Policy:** Submissions that are identical (or substantially similar) to versions that have been previously published, or accepted for publication, are not allowed and violate our dual submission policy.  However, papers that cite previous related work by the authors and papers that have appeared on non-peered reviewed websites (like arXiv) or that have been presented at workshops (i.e., venues that do not have publication proceedings) do not violate the policy. The policy is enforced during the whole reviewing process.

**Under-review Submissions:** For papers that are under review in another conference (e.g., EMNLP 2021), you can submit your paper to AKBC but must use the non-archival option. In addition, please also adhere to the rules set by the other conference. Specifically for EMNLP 2021, we will respect EMNLP’s anonymization period and will publicly announce AKBC accepted papers (archival and non-archival) after EMNLP notifications on Aug 25.


### Invited Talks
The following are confirmed invited speakers. Additional speakers are expected to be added.

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

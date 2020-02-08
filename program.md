---
layout: page
title: RCQA@AAAI
subtitle: Reasoning for Complex QA Workshop 2020
---


# Workshop Program

The following is a tentative schedule for the workshop -- we ask for your patience as we update the schedule to take into account conflicts and other constraints. The workshop will be held on February 8, 2020 (Saturday) as part of the [AAAI 2020 program](https://aaai.org/Conferences/AAAI-20/ws20/).

## Logistics

- Workshop Location: *Madison Suite* (Second Floor)
- Workshop Date: February 8, 2020 (Saturday)
- Workshop Location: *Hilton Midtown* Hotel, New York NY
- Workshop Questions: [ibm.biz/rcqa-qa](https://docs.google.com/presentation/d/e/2QANgcCBGtg9oOugqkYHuthxzUBc8z08eOLMnVAQAH8YJNlwIOsB6G_cvTZx0_StSKMv0pHQxHUx-OLn1qEw/askquestion?seriesId=7362e393-747f-470c-be17-070388e53f4b)

## Schedule

| **Time** 	| 	**Event** |
| ------------------ | ------------------ |
| 0850-0900 | 	Workshop Welcome |
| 0900-0930	| 	Invited Talk 1: [Ray Mooney](speakers.md#ray) |
| 0930-1040	| 	[Spotlight Talks](#spotlights) (7x10 mins each) |
| 1040-1110	|	Posters 1 (30 mins, overlaps with coffee break) |
| 1110-1140	| 	Invited Talk 2: [Nasrin Mostafazadeh](speakers.md#nasrin) |
| 1140-1200	|	Oral Paper 1: [Why Do Masked Neural Language Models Still Need Commonsense Knowledge?](https://rcqa-ws.github.io/papers/paper2.pdf) |
| 1200-1230	|	Invited Talk 3: [Bishan Yang](speakers.md#bishan) |
| 1230-1400	| 	Lunch (90 mins) |
| 1400-1430	| 	Invited Talk 4: [Robyn Speer](speakers.md#robyn) |
| 1430-1500	| 	Invited Talk 5: [Sameer Singh](speakers.md#sameer) |
| 1500-1600	|	[Open Poster Session](https://rcqa-ws.github.io/schedule/#open-poster-session), Posters 2 (60 mins, includes coffee break 1530-1600) |
| 1600-1620	|	Oral Paper 2: [Unsupervised Question Decomposition for Question Answering](https://rcqa-ws.github.io/papers/paper9.pdf) |
| 1620-1650	| 	Invited Talk 6: [Dan Roth](speakers.md#dan) |
| 1650-1700	| 	Workshop Close |

# Invited Speakers<a name="speakers"></a>

Invited talks will be 30 minutes each (25+5), and presented during their specific slots in the program. 

<div class="container">
  <div class="row">

{% for p in site.data.speakers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}

</div>
</div>

# Oral Presentations<a name="orals"></a>

The [oral presentations](https://rcqa-ws.github.io/schedule/#accepted-papers) will be 20 minutes each (15+5) and presented in the following order, in their specific slots in the program:

- Why Do Masked Neural Language Models Still Need Commonsense Knowledge?
- Unsupervised Question Decomposition for Question Answering

# Spotlight Presentations<a name="spotlights"></a>

The [spotlight presentations](https://rcqa-ws.github.io/schedule/#accepted-papers) will be 10 minutes each (8+2) and will all be presented in the first session of the workshop. This is to enable maximum discussion time during both poster sessions. The spotlights will be presented in the following order:

- SMAC: An Interpretable Reasoning Network for Visual Question Answering
- Supervised Understanding of Word Embeddings
- Online Discussion Facilitation Support
- Giving Commands to a Self-driving Car: A Multimodal Reasoner for Visual Grounding
- Generating Helpful Responses for Intelligent Tech Support
- Humor Detection based on Paragraph Decomposition and BERT Fine-Tuning
- SymbolNet: A Neural Symbolic Approach with Numerically-aware Graph for Discrete Reasoning Over Paragraphs
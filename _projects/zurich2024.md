---
layout: page
title: Zurich 2024 Meeting
description: Kick-off Meeting, 4–5 July 2024
img: assets/img/meetups/zurich2024-crop.jpg
importance: 2
category: Meetups
giscus_comments: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/meetups/zurich2024.jpg" title="Zurich July 2024" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<!-- div class="caption">
    This image can also have a caption. It's like magic.
</div -->

The kick-off meeting launched the **Neurosymbolic AI for Medicine** network, bringing together researchers to define how neural learning and symbolic reasoning can be combined for safer, more transparent medical AI. Participants discussed definitions and boundaries of NeSy systems, their importance for integrating diverse medical data and clinical knowledge, and the challenges of bias, explainability, and regulation. The network agreed to produce a **white paper and roadmap**, and build a shared platform for collaboration and resources—laying the foundation for a global community advancing trustworthy, knowledge-driven AI in healthcare.


### Agenda

**Day 1 — Internal Network Kick-off Meeting**
_UZH Main Building, Rämistrasse 71, Room KOL-F-123_

**11:00 – 12:30** — _Introductions and Discussion_  
Definition of Neuro-Symbolic AI in Medicine; challenges, opportunities, and the motivation for establishing the network.

**12:30 – 13:30** — _Lunch_

**13:30 – 14:30** — _White Paper Brainstorming_  
Outline, structure, responsibilities, and workplan for a community white paper.

**14:30 – 15:30** — _Network Activities Discussion_  
Ideas for publicity, special journal issues, future meetings, grant opportunities, and community growth.

**15:30 – 16:00** — _Coffee Break_

**16:00 – 17:30** — _Case Studies Deep Dive_  
Exploring clinical and medical scenarios suitable for NeSy-AI methods; current progress and research gaps.

**19:00+** — _Dinner at Osteria Borgo_

---

**Day 2 — AMS Network & DSI Health Workshop**
_DSI Event Room, Rämistrasse 69, 8001 Zürich_  
_Part of the DSI Health Seminar Series: “Machine Learning in Health that Matters”_
[Event link](https://health.dsi.uzh.ch/news/save-the-date-machine-learning-in-health-that-matters-july-5th/)

**Morning Session**
**09:00 – 09:10** — _Welcome_ — Ernesto & Janna  
**09:10 – 09:30** — _Introduction to the AMS Network NSAI-Med_ — Ernesto & Janna  
**09:30 – 10:00** — _Neural-symbolic Knowledge Representation with Ontology and KG Embeddings_ — Jiaoyan Chen ([Slides](assets/pdf/meetups/zurich-jiaoyan.pdf)) 
**10:00 – 10:30** — _What do Knowledge Graph Embeddings Actually Learn?_ — Heiko Paulheim  
**10:30 – 11:00** — _Coffee Break_  
**11:00 – 11:20** — _Neurosymbolic Techniques for Relation Extraction from Text_ — V. Raghava Mutharaju  ([Slides](assets/pdf/meetups/zurich-raghava.pdf))
**11:20 – 12:40** — _Neuro-symbolic Approaches for Knowledge Graph Refinement and Explanations_ — Claudia D'Amato ([Slides](assets/pdf/meetups/zurich-claudia.pdf))  
**11:40 – 12:00** — _BioBLP: A modular framework for representation learning over biomedical knowledge graphs_ — Michael Cochez ([Slides](assets/pdf/meetups/zurich-michael.pdf))
**12:00 – 12:30** — _Considerations for Pediatric AI/ML from a Global Health Perspective_ — Joel Schamroth  
**12:30 – 13:30** — _Lunch_


**Afternoon Session — Hackathon / Promptathon**
**13:30 – 14:00** — Topic pitches: _LLMs and Knowledge Graphs for Medicine_  
**14:00 – 16:00** — Group work sessions (with coffee at 15:00)  
**16:00 – 16:30** — Feedback presentations from groups

**Evening Session**
**17:00 – 18:00** — _Keynote: “Machine Learning in Health that Matters – Building an AI-Ready World”_ — Leo Anthony Celi  
**18:00 – 19:00** — _Apéro and Networking_  
**19:30+** — _Dinner at Brasserie Johanniter_

---

### Outcomes and Discussions

The meeting established a shared vision for **Neurosymbolic AI in Medicine**:  
to develop hybrid systems that combine the learning power of neural models with the transparency, reasoning, and domain knowledge of symbolic approaches—toward safer, fairer, and more trustworthy medical AI.

#### Defining Neurosymbolic AI

Participants discussed how to define _neurosymbolic AI (NeSy-AI)_, highlighting the tension between narrow definitions—where neural and symbolic components are tightly integrated—and broader interpretations that include systems such as knowledge-graph embeddings or neural models interacting with symbolic reasoners.

The group agreed that **LLMs are not inherently neurosymbolic**, though they can become so when combined with reasoning or planning modules. Six categories of NeSy systems were reviewed, ranging from loosely coupled hybrids to hypothetical, fully integrated architectures.

---

#### Why NeSy-AI is Essential in Medicine

NeSy-AI can address core limitations of current deep-learning systems by enabling:

- **Integration of diverse data sources** (imaging, text, genomics, clinical records)
- **Incorporation of biomedical knowledge** (ontologies such as SNOMED, UMLS, Gene Ontology)
- **Transparent and verifiable reasoning**, essential for clinical safety and regulation
- **Improved performance with small or biased datasets** through symbolic constraints and transfer learning
- **Multimodal and process-level reasoning** for complex care pathways and causal relationships

---

#### Challenges and Barriers

Key obstacles identified include:

- Limited **regulatory clarity** and liability frameworks for AI-assisted decision-making
- **Poor data capture and documentation**, with little clinician incentive to record structured information
- **Disconnect between ontologies and clinical reality**, reducing applicability
- Risk of **systematic bias and errors** in both human and AI decision processes

---

#### Opportunities and Use Cases

NeSy-AI offers promising applications such as:

- **Human-in-the-loop systems** maintaining clinician control
- **Explainable medical imaging** and artefact detection
- **Drug repurposing and personalised medicine**
- **Clinical documentation assistance** and multimodal reasoning
- **Symbolic bias-mitigation and fairness checking**

---

#### Discussion on Bias (Day 2)

The Bias Working Group meeting, led by researchers from City, University of London, the Universities of Bari and Liverpool, Harvard, and others, focused on examining and demonstrating bias in large language models (LLMs) within clinical contexts. The group aims to show how identical prompts can yield inconsistent or biased outputs, including cases where minor changes such as mentioning a patient’s race affect diagnostic suggestions. Members discussed testing LLM reliability using false or misleading statements, evaluating prompt formats (zero-shot vs. dialogue modes), and assessing how patient history influences responses. They proposed developing guidance for clinicians on safe and effective prompt engineering, alongside a qualitative framework to label prompts and responses according to their risk of bias or inconsistency. Relevant recent studies and resources were shared to inform this work.

---

#### Network Plans and Actions

- Draft a **white paper and roadmap** defining priorities and opportunities for NeSy-AI in medicine
- **Organise a workshop** with leading researchers (target: 2025)
- Build a **community platform** (GitHub, website, social media) for datasets, teaching materials, and collaboration
- Pursue **funding opportunities** (EPSRC, COST, HDR UK, EU Horizon) and foster consortia for larger projects
- Conduct **case studies** on clinical scenarios (e.g., preterm care, imaging artefacts) to demonstrate impact

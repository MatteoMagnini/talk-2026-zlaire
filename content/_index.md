+++
title = "The New Wave of Agentic AI"
description = "Main Challenges and Research Directions"
outputs = ["Reveal"]
+++

{{% section %}}

# The New Wave of Agentic AI:
## Main Challenges and Research Directions

<span class="hint">(last built on: {{< today >}})</span>


{{< mm >}}

<br> Postdoctoral Researcher
<br> Department of Computer Science
<br> University of Luxembourg

<br>ZLAIRE Workshop
<br>28th May 2026, Zhejiang University, Hangzhou

<br>

---

## Link to these slides

<{{< slides-url >}}>

{{< qrcode >}}

[<i class="fa fa-print" aria-hidden="true"></i> printable version](?print-pdf&pdfSeparateFragments=false)

{{% /section %}}

---
{{% section %}}

{{< slide id="agents-history" >}}

# Agents Are Not New

<br>

## Agents predate modern agentic AI by decades
[The Agents Journey](https://doi.org/10.1007/978-3-032-22940-3) -- Twenty-Five Years of Multi-agent Systems (2026)


<br>

{{% multicol class="multicol-centered"%}}

{{% col %}}

### Historical roots
- Distributed Systems
- Artificial Intelligence
- Multi-Agent Systems
- Robotics
- Control Systems

{{% /col %}}

{{% col %}}

### Long-standing research themes
- Autonomy
- Planning
- Coordination
- (Self) Organization
- Simulation

{{% /col %}}

{{% /multicol %}}

---

## Today we are witnessing

{{% multicol class="multicol-centered"%}}

{{% col %}}

### New paradigms/technologies
- Neuro-Symbolic AI
- __Large Language Models__
- Agentic AI frameworks
- __Swarm intelligence/robotics__

{{% /col %}}

{{% col %}}

### Hot topics
- Agentic Automation
- __Normative AI__
- AI safety and trustworthiness
- AI governance and regulation

{{% /col %}}

{{% /multicol %}}
 
---

## Trends
<br>

{{% multicol class="multicol-centered"%}}

{{% col %}}

### Pervasive AI
- AI is everywhere
- Everyone is using LLMs

{{< image src="./images/estimated-share-people-generative-ai.png" alt="Estimated share of people using generative AI" width="90%" >}}

{{% /col %}}
{{% col %}}

### Embodied Agents
- Not just chatbots or digital agents
- Physical robots, drones, vehicles

{{< image src="./images/self-driving-bus-belval.jpeg" alt="Self-driving bus in Belval" width="90%" >}}

{{% /col %}}

{{% /multicol %}}

{{% /section %}}

---

{{% section %}}

{{< slide id="research-directions" >}}

# Anticipating the future
<br>

It is just a matter of time before we see a considerable number of __embodied agents__ in public places.

Also, the nature of these embodied agents will be __heterogeneous__, with different capabilities and tasks.

Their presence in the society will raise many challenges, including __ethical__, legal, social, and technical ones.

<div style="text-align:center; font-size:2em;">↓</div>

Need for building __embodied agents__ with __ethics__ as a core design principle.

---

## Defensible Embodied Agents

{{% multicol %}}

{{% col %}}

### Defensible
__Defensible__ refers to the ability of a decision, action, or system to be __justified, challenged, audited, and publicly explained__ through sufficient evidence and reasoning.
A defensible system is not merely effective or safe: it must also support accountability, contestability, and governance.

{{% /col %}}

{{% col %}}

### Embodied
__Embodied__ means that something or someone has a __physical__ form in the __real world__, as opposed to being purely digital or virtual.
Embodied agents can interact with their environment, other agents and humans in a tangible way.

{{% /col %}}

{{% col %}}

### Agents
Agent comes from "agere", i.e., __to act__.
An agent is an entity that can perceive its environment, make decisions, and take actions to achieve specific goals or objectives.
It is __autonomous__, (possibly) self-sufficient, __proactive__, and (possibly) adaptive.

{{% /col %}}

{{% /multicol %}}

---

## Why embodied?

Purely __digital agents__, such as chatbots, have __great limitations__.

The knowledge at their disposal is obtained by training on huge amount of text.

Interaction is just a stochastic process of predicting the next token.

<br>

Chatbots (usually) do not have a __model of the world__, their "world" is just the conversation.

Other digital agents can receive data from the real world and maybe even have control of some actuators, but they are not "embodied".

Their sensing and actions are limited to a very specific scope.

Sensors and actuators are not part of their body, but just __external devices__ that they can use.

---

## _The best model of the world is the world itself_

{{<image src="./images/models-wrong-useful.avif" alt="All models are wrong, but some are useful" width="80%" >}}

{{% /section %}}

---

{{% section %}}

{{< slide id="papers" >}}

# Papers related to the projects
<br>


{{% multicol %}}

{{% col %}}
## "You are Orthos"
- "You are Orthos": An Experiment in AI-Assisted Human-Rights-Based Reasoning for Content Moderation Disputes under the Digital Services Act
- [zenodo.org/record/19311283](https://zenodo.org/record/19311283)
- Key Ideas:
  - AI-assisted framework for content moderation disputes
  - Generation of rulings based on human rights principles
  - Expert evaluation of persuasiveness and consistency
  - Implications for AI in legal decision support

{{% /col %}}

{{% col %}}

## NL2UNIFOL
- NL2UNIFOL: from Natural Language Sentences to Uniform First-Order Logic Formulae
- Submitted to SKILLED-LLM (FLoC WS)
- Key Ideas:
  - LLM norm translation is commonly done at sentence level
  - No shared vocabulary among formulae/norms for terms and predicates
  - We propose a framework for unifying the vocabulary
  - Future work: use modal logic

{{% /col %}}

{{% col %}}

## AGE-ML
- AGE-ML: A Data-Centric, Specification-Driven Architecture for Agentic AutoML
- Submitted to Future Generation Computer Systems (FGCS)
- Key Ideas:
  - Automation end-to-end of the entire ML lifecycle
  - Agentic architecture with multiple specialized agents
  - User's specification to guide the process
  - Explainability and human-in-the-loop for oversight and control

{{% /col %}}

{{% /multicol %}}

{{% /section %}}

---

{{% section %}}

{{< slide id="connections" >}}

# Possible Connections Across Groups

<br>

{{% multicol class="multicol-centered" %}}

{{% col %}}

## ICR
- Agentic workflows
- Neuro-symbolic AI
- Human-in-the-loop systems
- Multi-agent orchestration

{{% /col %}}

{{% col %}}

## CLAIM
- Normative AI
- Formal verification
- AI governance
- Compliance-aware systems

{{% /col %}}

{{% col %}}

## TAI
- Human-centric AI
- Trustworthy AI
- AI safety
- Responsible LLMs

{{% /col %}}

{{% /multicol %}}

<br>

## Shared Directions
- Norm-aware AI agents
- Verification for autonomous systems
- AI-assisted legal reasoning
- Governance for agentic AI

{{% /section %}}

---

{{% section %}}

{{< slide id="collaboration" >}}

# Collaboration Opportunities

<br>

{{% multicol %}}

{{% col %}}

## Student Projects
- High student interest in AI projects
- Currently supervising 6–7 students
- Opportunity for co-supervision
- Shared thesis/project ideas

{{% /col %}}

{{% col %}}

## GitHub Organization
- Shared repositories
- Unified project templates
- Shared datasets/resources

{{% /col %}}

{{% col %}}

## Example Repositories
- `student-projects`
- `research-projects`
- `documents`
- `datasets`

{{% /col %}}

{{% /multicol %}}

{{% /section %}}

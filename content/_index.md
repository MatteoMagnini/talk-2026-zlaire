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

{{< slide id="outline" >}}

# Outline

<br>

This talk is about my personal perspective on the current state and future directions of agentic AI research.

In particular, it is focused on __Embodied Agents__ and how should we design them from an __ethical__ point of view.

These slides are partially inspired by the many talks I had with the groups in these days on this topic, and also, by the staying in Hangzhou.

<br>

Slides are structured as follows:

- [Agents are not new](#agents-history)

- [Anticipating the future](#research-directions)

- [Why defensible?](#why-defensible)

- [Why embodied?](#why-embodied)

- [Why agents?](#why-agents)

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

{{% /section %}}

---

{{% section %}}

{{< slide id="why-defensible" >}}

# Why defensible?

{{% multicol %}}

{{% col %}}

Modern embodied agents will increasingly operate in shared human environments:
- Schools
- Hospitals
- Public transportation
- Homes
- Workplaces

{{% /col %}}

{{% col %}}

In these contexts, __pure optimization__ is not enough.

An agent should not only ask:
- "What can I do?"

but also:
- "What should I do?"
- "What am I allowed to do?"
- "How should I behave with humans?"

{{% /col %}}

{{% col %}}

This requires explicit representations of:

- Permissions
- Obligations
- Prohibitions
- Preferences
- Social conventions
- Ethical principles

{{% /col %}}

{{% /multicol %}}

---

## From rule-following to defensibility

{{% multicol class="multicol-centered"%}}

{{% col %}}

A defensible agent is not simply:
- __compliant__
- accurate
- __safe__

{{% /col %}}

{{% col %}}

It must also be able to:
- __justify__ its decisions
- expose the reasoning process
- support contestability
- provide __explanations__ understandable by humans

{{% /col %}}

{{% /multicol %}}

<br>
<br>

<div style="text-align:center; font-size:1.2em;">
Effective AI → Responsible AI → Defensible AI
</div>

---

## DJ4ME

### A DJ for Machine Ethics: the Dialogue Jiminy

{{< image src="./images/dj4me.png" alt="DJ4ME" width="80%" >}}

{{% multicol class="multicol-centered"%}}

{{% col %}}

Different stakeholders may have:
- __different objectives__
- __different values__
- different expectations

{{% /col %}}

{{% col %}}

Examples:
- final __users__
- providers
- institutions/regulators
- domain experts

{{% /col %}}

{{% /multicol %}}

---

## Conflict resolution

Using the __Jiminy__ framework ([The Jiminy Advisor: Moral Agreements Among Stakeholders Based on Norms and Argumentation](https://doi.org/10.1613/jair.1.14368)).

{{% multicol %}}

{{% col %}}

Each stakeholder is modeled as a __normative system__:
- obligations
- permissions
- prohibitions
- contextual preferences

These normative systems are then used as sources of __arguments__.

{{% /col %}}

{{% col %}}

Instead of relying on majority voting or fixed priorities,
Jiminy tries to reach a __moral agreement__ among stakeholders.

The framework resolves dilemmas through:
- interactions between arguments
- attacks and defenses
- argument acceptability semantics

{{% /col %}}

{{% /multicol %}}

---

<!--
## Moral agreements

Jiminy proposes three complementary mechanisms:

1. __Argument interaction__
   - conflicts may already be resolved through the structure of the arguments themselves

2. __Normative combination__
   - stakeholders' normative systems can be combined
   - new arguments may emerge from the combined knowledge

3. __Context-sensitive priorities__
   - only when necessary, contextual rules determine which stakeholder takes precedence

<br>

At the abstract level, these mechanisms correspond to:
- adding arguments
- adding attacks
- revising attacks

within the argumentation framework.

---
-->

## Explainability

{{% multicol class="multicol-centered"%}}

{{% col %}}

### Resolving conflicts is not enough

The system must also explain:
- why a decision was taken
- which norms were considered
- which arguments prevailed
- why alternative actions were rejected

{{% /col %}}

{{% col %}}

Argumentation naturally supports explainability,
because decisions emerge from explicit reasoning structures.

Therefore, DJ4ME includes an additional agent dedicated to making decisions:
- __auditable__
- inspectable
- contestable
- __publicly explainable__

{{% /col %}}

{{% /multicol %}}

---

## AI4Kids

### Safe child-facing embodied AI

{{% multicol %}}

{{% col %}}

<br>
<br>

Children are increasingly exposed to:
- __conversational AI__
- __tutoring systems__
- social robots

However, most existing AI systems are designed for adults.

{{% /col %}}

{{% col %}}

<br>
<br>

This is particularly problematic in sensitive domains such as:
- __education__
- __therapy__
- special needs support

where safety, trust, and controllability become essential requirements.

{{% /col %}}

{{% col %}}

{{< image src="./images/qtrobot.webp" alt="QTrobot" width="80%" >}}

<div align="center">

QTrobot from
[LuxAI](https://luxai.com/)

</div>

{{% /col %}}

{{% /multicol %}}

---

## A norm-first architecture

AI4Kids investigates how to __safely integrate LLMs__ into embodied agents.

Core idea: LLMs should not operate autonomously, but inside a constrained cognitive architecture.

{{% multicol %}}

{{% col %}}

The project develops a __norm-first agent architecture__ where:
- LLMs provide flexible dialogue capabilities
- __Norms constrain the reasoning cycle__
- Machine-readable policies enforce safety checks

{{% /col %}}

{{% col %}}

This enables behavior that is:
- __Explainable__
- __Auditable__
- Regulation-aware
- Compliant-by-design

{{% /col %}}

{{% col %}}

Research challenges:
- Age-appropriate dialogue
- __Safe interaction__
- Controllability
- Robustness against unsafe outputs

{{% /col %}}

{{% /multicol %}}

{{% /section %}}

---

{{% section %}}

{{< slide id="why-embodied" >}}

# Why embodied?

<br>

Purely __digital agents__, such as chatbots, have many limitations.

The knowledge at their disposal is obtained by training on huge amount of text.

Interaction is often reduced to a stochastic process of predicting the next token.

{{% multicol class="multicol-centered"%}}

{{% col %}}

Chatbots __do not directly experience__ the world.
Their knowledge is mediated through:
- documents
- conversations
- descriptions written by humans

{{% /col %}}

{{% col %}}

As a consequence:
- their internal models may contain __biases__
- information may be incomplete or __outdated__
- grounding in physical reality is limited

{{% /col %}}

{{% /multicol %}}

---

## Digital agents vs embodied agents

<br>

{{% multicol %}}

{{% col %}}

### Digital agents
- Mainly operate in __virtual environments__
- Interact through text or software APIs
- Can use software tools
- __No/Limited physical awareness__
- __No direct interaction with the world__

{{% /col %}}

{{% col %}}

### Embodied agents
- __Perceive the physical world directly__
- __Interact__ through sensors and actuators
- Learn from situated interaction
- __Affect real environments and humans__
- Must reason about __safety__ and __uncertainty__

{{% /col %}}

{{% col %}}

### This introduces new challenges
- __Real-time decision-making__
- Uncertainty and partial observability
- __Safety-critical behavior__
- Social interaction
- Accountability

{{% /col %}}

{{% /multicol %}}

---

## Which kind of embodied agents?

<br>

{{% multicol class="multicol-centered"%}}

{{% col %}}

### Controlled environments
- Manufacturing robots
- Warehouse automation
- Cleaning robots
- Restaurant/service robotics

These systems operate in relatively predictable environments and focus on efficiency, precision, and repeatability.

{{% /col %}}

{{% col %}}

### Human-centered environments
- Caregiving robots
- Educational robots
- Assistive systems
- Housekeepers
- Collaborative robots

These agents must interact safely and naturally with humans in dynamic social contexts.

{{% /col %}}

{{% /multicol %}}

{{% /section %}}

---

{{% section %}}

{{< slide id="why-agents" >}}

# Why agents?

We all know the reasons why we need __agents__ and not just __passive tools__.

{{% multicol class="multicol-centered"%}}

{{% col %}}

### By capability
- Mono-task agents
- Multi-task agents
- General-purpose agents

{{% /col %}}

{{% col %}}

### By organization
- Single-agent systems
- Multi-agent systems
- Swarm systems

{{% /col %}}

{{% /multicol %}}

___

## Collection of robots I saw in Hangzhou

{{% multicol %}}

{{% col %}}

{{< image src="./images/coffee-robot.png" alt="Coffee robot" weight="60%" >}}


{{< image src="./images/food-delivery-robot.png" alt="Food delivery robot" weight="60%" >}}

{{% /col %}}

{{% col %}}

{{< image src="./images/agriculture-robot.png" alt="Agriculture robot" weight="60%" >}}


{{< image src="./images/dog-robot.png" alt="Dog robot" weight="60%" >}}

{{% /col %}}

{{% col %}}

{{< image src="./images/space-explorer.jpg" alt="Space explorer robot" weight="60%" >}}


{{< video src="./videos/barman-robot.MOV" alt="Barman robot" weight="60%" autoplay="true" muted="true" loop="true" >}}

{{% /col %}}

{{% /multicol %}}

{{% /section %}}


---
title: 'ICLR 2019 Task-Agnostic Reinforcement Learning Workshop'
layout: default
---

<style>thead { display: none; }</style>

## Summary

Many of the successes in deep learning build upon rich supervision.
Reinforcement learning (RL) is no exception to this: algorithms for locomotion,
manipulation, and game playing often rely on carefully crafted reward functions
that guide the agent. But defining dense rewards becomes impractical for
complex tasks. Moreover, attempts to do so frequently result in agents
exploiting human error in the specification. To scale RL to the next level of
difficulty, agents will have to learn autonomously in the absence of rewards.

We define task-agnostic reinforcement learning (TARL) as learning in an
environment without rewards to later quickly solve down-steam tasks. Active
research questions in TARL include designing objectives for intrinsic
motivation and exploration, learning unsupervised task or goal spaces, global
exploration, learning world models, and unsupervised skill discovery. The main
goal of this workshop is to bring together researchers in RL and investigate
novel directions to learning task-agnostic representations with the objective
of advancing the field towards more scalable and effective solutions in RL.

<p style="text-align: left">
We invite paper submissions in the following categories to present at the
workshop:
</p>

- Unsupervised objectives for agents
- Curiosity and intrinsic motivation
- Few shot reinforcement learning
- Model-based planning and exploration
- Representation learning for planning
- Learning unsupervised goal spaces
- Unsupervised skill discovery
- Evaluation of unsupervised agents

## Speakers

Please submit questions for our panel discussion: <a href="https://forms.gle/F41KfB9ANka5kkuJ8 ">https://forms.gle/F41KfB9ANka5kkuJ8</a>

<div style="text-align: left;">
{%- for person in site.data.speakers -%}
<div class="person">
  <img src="{{ person.image }}" />
  <a href="{{ person.url | relative_url }}">{{ person.name }}</a><br>
  <span>{{ person.title | replace: '&', '<br>' }}</span>
  <!--span>({{ person.topics }})</span-->
</div>
{%- endfor -%}
</div>

## Dates

| Event | Date |
| ----- | ---- |
| Submission deadline | **29 March 2019** (11:59 pm [AOE][aoe]) |
| Notifications | **23 April 2019** |
| Camera ready | **04 May 2019** (11:59 pm [AOE][aoe]) |
| Workshop | **06 May 2019** |

[aoe]: https://www.timeanddate.com/time/zones/aoe

## Sponsors

We thank our sponsors for making this workshop possible:

<div style="text-align: left;">
{%- for sponsor in site.data.sponsors -%}
<div class="sponsor">
  <a href="{{ sponsor.url }}" target="_blank">
    <img src="{{ sponsor.image }}" />
  </a>
</div>
{%- endfor -%}
</div>

## Schedule

| Time | Event |
| ---- | ----- |
| 09:45 | Opening |
| 09:50 | **Invited talk** – [Martin Riedmiller][martin]: *Internal Reward Predicates for Task Agnostic RL* |
| 10:20 | **Lightning talks** |
| 10:30 | **Posters** + Coffee break |
| 11:00 | **Invited talk** – [Chelsea Finn][chelsea]: *What can we Learn from Unlabeled Interaction?* |
| 11:30 | **Invited talk** – [Doina Precup][doina]: *Generalized Value Functions: Knowledge Representation for RL agents* |
| 12:00 | **Contributed talk** – [Vitchyr Pong][vitchyr]: *Skew-Fit: State-Covering Self-Supervised Reinforcement Learning* |
| 12:15 | **Contributed talk** – [Lisa Lee][lisa]: *State Marginal Matching with Mixtures of Policies* |
| 12:30 | **Invited talk** – [Katja Hofmann][katja]: *Directions and Challenges in Multi-Task Reinforcement Learning* |
| 13:00 | Lunch break |
| 15:20 | **Contributed talk** – [Corey Lynch][corey]: *Learning Latent Plans from Play Data* |
| 15:35 | **Contributed talk** – [Hugo Caselles-Dupré][hugo]: *Symmetry-Based Disentangled Representation Learning requires Interaction with Environments* |
| 15:50 | **Lightning talks** |
| 16:00 | **Posters** + Coffee break |
| 16:30 | **Invited talk** – [Pierre-Yves Oudeyer][pierre]: *Curiosity-driven exploration of learned goal spaces: Discovering independently controllable features* |
| 17:00 | **Invited talk** – [Neil Bramley][neil]: *Intuitive experimentation in human and artificial agents* |
| 17:30 | **Panel discussion** |
| 18:00 | End |

[speakers]: #speakers
[martin]: https://scholar.google.ca/citations?user=DdOazFIAAAAJ&hl=en
[chelsea]: http://people.eecs.berkeley.edu/~cbfinn/
[doina]: https://www.cs.mcgill.ca/~dprecup/
[katja]: https://www.microsoft.com/en-us/research/people/kahofman/
[pierre]: http://www.pyoudeyer.com/
[neil]: https://www.bramleylab.ppls.ed.ac.uk/member/neil/
[vitchyr]: http://people.eecs.berkeley.edu/~vitchyr/
[lisa]: https://leelisa.com/
[corey]: https://scholar.google.com/citations?user=CYWO-oAAAAAJ&hl=en
[hugo]: https://sites.google.com/view/hugo-caselles-dupre

## Submissions

Papers should be in anonymous ICLR style and **up to 5 pages**, with an
unlimited number of pages for references and appendix. Accepted papers will be
presented during our poster session and made available on the workshop website.
Selected authors will be offered a 10 min talk at the workshop. This does not
constitute an archival publication and no formal workshop proceedings will be
made available, meaning contributors are free to publish their work at journals
or conferences.

<!--p style="text-align: left">
Start a submission: <a href="https://cmt3.research.microsoft.com/tarl2019">https://cmt3.research.microsoft.com/tarl2019</a>
</p-->

Submissions are now closed. Thanks to everyone for submitting!

Paper portal: <a href="https://cmt3.research.microsoft.com/tarl2019">https://cmt3.research.microsoft.com/tarl2019</a>

## Accepted papers

We've received many interesting and high-quality submissions, out of which we
accepted 24 papers to be presented at our poster sessions. The order below was
selected randomly and the PDFs will be made available here after the camera-ready
date.

<div style="text-align: left;">
{%- for paper in site.data.papers -%}
<div class="paper">
  <h3>{{ paper.title }}</h3>
  <p>{{ paper.authors }}</p>
</div>
{%- endfor -%}
</div>

## Organizers

<div style="text-align: left;">
{%- for person in site.data.organizers -%}
<div class="person">
  <img src="{{ person.image }}" />
  <a href="{{ person.url | relative_url }}">{{ person.name }}</a><br>
  <span>{{ person.title | replace: '&', '<br>' }}</span>
</div>
{%- endfor -%}
</div>

<p style="text-align: left">
For questions, please contact us at:
<a href="mailto:taskagnosticrl@gmail.com">taskagnosticrl@gmail.com</a>
</p>

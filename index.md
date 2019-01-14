---
title: 'ICLR 2019 Task-Agnostic Reinforcement Learning Workshop'
layout: default
---

## Abstract

Many of the successes in deep learning build upon rich supervision.
Reinforcement learning (RL) is no exception to this: algorithms for locomotion,
manipulation, and game playing often rely on carefully crafted reward functions
that guide the agent. But defining dense rewards becomes impractical for
complex tasks. Moreover, attempts to do so frequently result in agents
exploiting human error in the specification. To scale RL to the next level of
difficulty, agents will have to learn autonomously in the absence of rewards.
We define task-agnostic reinforcement learning (TARL) as learning in an
environment without rewards to later qickly solve down-steam tasks. Active
research questions in TARL include designing objectives for intrinsic
motivation and exploration, learning unsupervised task or goal spaces, global
exploration, learning world models, and unsupervised skill discovery. The main
goal of this workshop is to bring together researchers in RL and investigate
novel directions to learning task-agnostic representations with the objective
of advancing the field towards more scalable and effective solutions in RL.

We invite paper submissions in the following categories to present at the
workshop:

- Unsupervised objectives for agents
- Curiosity and intrinsic motivation
- Few shot reinforcement learning
- Model-based planning and exploration
- Representation learning for planning
- Learning unsupervised goal spaces
- Automated curriculum generation
- Unsupervised skill discovery
- Evaluation of unsupervised agents

For question, please send us an email to
[tarl@reinforcement-learning.ml](mailto:tarl@reinforcement-learning.ml).

## Important Dates

Submission deadline: **29 March 2019** ([Anywhere on Earth][aoe]) <br>
Notification: **2019** <br>
Camera ready: **04 May 2019** <br>
Workshop: **May 2019**

[aoe]: https://www.timeanddate.com/time/zones/aoe

## Speakers

Coming soon.

## Submission instructions

Papers should be in ICLR style and **up to 5 pages**, with an unlimited number
of pages for references and appendix. Accepted papers will be made available on
the workshop website and selected authors will be offered a 15 min talk at the
workshop. This does not constitute an archival publication and no formal
workshop proceedings will be made available, meaning contributors are free to
publish their work at journals or conferences.

Start a submission: [https://cmt3.research.microsoft.com/tarl2019](https://cmt3.research.microsoft.com/tarl2019)

## Schedule

| Time | Event |
| ---- | ----- |
| 08:45 | Introduction and opening remarks |
| 09:00 | **Invited Talk 1** – TBD |
| 09:30 | **Invited Talk 2** – TBD |
| 10:00 | Poster Session 1 + Coffee Break |
| 11:00 | **Contributed Talk 1** – TBD |
| 11:20 | **Contributed Talk 2** – TBD |
| 11:40 | **Contributed Talk 3** – TBD |
| 12:00 | *Lunch Break* |
| 13:30 | **Invited Talk 3** – TBD |
| 14:00 | **Contributed Talk 4** – TBD |
| 14:20 | **Contributed Talk 5** – TBD |
| 14:20 | **Contributed Talk 6** – TBD |
| 15:00 | Poster Session 2 + Coffee Break |
| 16:00 | **Invited Talk 4** – TBD |
| 16:00 | **Invited Talk 5** – TBD |
| 17:00 | Panel discussion |
| 18:00 | End |

## Organizers

<div class="organizers">
{%- for organizer in site.data.organizers -%}
  <div>
    <img src="{{ organizer.image }}" />
    <a href="{{ organizer.url | relative_url }}">{{ organizer.name }}</a><br>
    <span>{{ organizer.title | replace: '&', '<br>' }}</span>
  </div>
{%- endfor -%}
</div>

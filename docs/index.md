---
title: Overview
summary: Blog landing page.
authors: Jon Harper
date: 2022-06-16
---

![What I May or May Not Look Like](img/doug.png){ data-title="I Kinda Look Like This" data-description="Sorta." width="250px" align="right" }

I'm a technology- and information-oriented problem solver. I love:

- writing to document and educate;
- teaching and discussing ideas and concepts;
- designing 3D printable, practical solutions;
- developing in C++ and reading about the nuances of the language;
- scripting in Python to simplify tasks; and
- the "ah-ha!" of understanding and sharing that feeling with others.

You can find out more on my [about page](about.md).

## Projects

{% import 'assets/macros/cards.md' as cards with context %}
{{ cards.start_grid(3) }}
{{ cards.add_card(title="OmniBox", content="A modular, 3D-printable electronics case for 3D printers.", image="../img/omnibox_logo.png", url="projects/omnibox/") }}
{{ cards.add_card(title="Clock 3", content="A prototype enclosed 3D printer used as a testbed for new ideas.", image="../img/clock3.png", url="projects/clock3/") }}
{{ cards.add_card(title="The Clockmaker Project", content="Tools and guides for enclosed 3D printing.", image="../img/clockmaker.png", url="projects/clockmaker/") }}
{{ cards.end_grid() }}

## Public Efforts and Other Works

{{ cards.start_grid(3) }}
{{ cards.add_card(title="GitHub", content="", image="../img/github.png", url="https://github.com/jon-harper/") }}
{{ cards.add_card(title="Stack Overflow", content="", image="../img/stackoverflow.png", url="https://stackoverflow.com/users/4732082/jonspaceharper") }}
{{ cards.add_card(title="Thingiverse", content="", image="../img/thingiverse.png", url="https://www.thingiverse.com/jonspaceharper/designs") }}
{{ cards.end_grid() }}

## Contact

{% import 'assets/macros/cards.md' as cards with context %}
{{ cards.start_grid(3) }}
{{ cards.add_card(title="LinkedIn", content="", image="../img/linkedin.png", url="https://linkedin.com/in/jonspaceharper") }}
{{ cards.add_card(title="Reddit", content="", image="../img/reddit.png", url="https://www.reddit.com/user/jonspaceharper") }}
{{ cards.end_grid() }}

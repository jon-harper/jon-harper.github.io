---
title: Overview
summary: Blog landing page.
authors: Jon Harper
date: 2022-06-16
---

![What I May or May Not Look Like](img/doug.png){ data-title="I Kinda Look Like This" data-description="Sorta." width="250px" align="right" }

I'm a technology- and information-oriented problem solver. I love to:

- **write** to document and educate;
- **teach** and discuss ideas and concepts;
- **design** 3D printable, practical solutions;
- **develop** in C++ and learn the nuances of the language;
- **script** in Python to simplify tasks; and
- **learn** new technologies and ideas.

You can find out more on my [about page](about.md).

## Projects

These are the projects that I currently develop/maintain.

{% import 'assets/macros/cards.md' as cards with context %}
{{ cards.start_grid(3) }}
{{ cards.add_card(title="OmniBox", content="A modular, 3D-printable electronics case for 3D printers.", image="../img/omnibox_logo.png", url="projects/omnibox/") }}
{{ cards.add_card(title="Clock 3", content="A prototype enclosed 3D printer used as a testbed for new ideas.", image="../img/clock3.png", url="projects/clock3/") }}
{{ cards.add_card(title="The Clockmaker Project", content="Tools and guides for enclosed 3D printing.", image="../img/clockmaker.png", url="projects/clockmaker/") }}
{{ cards.end_grid() }}

## Public Efforts and Other Works

{{ cards.start_grid(3) }}
{{ cards.add_card(title="GitHub", content="GitHub hosts my large 3D projects and some of my programming work.", image="../img/github.png", url="https://github.com/jon-harper/") }}
{{ cards.add_card(title="Stack Overflow", content="The world's largest programming question and answer site.", image="../img/stackoverflow.png", url="https://stackoverflow.com/users/4732082/jonspaceharper") }}
<!-- {{ cards.add_card(title="Thingiverse", content="", image="../img/thingiverse.png", url="https://www.thingiverse.com/jonspaceharper/designs") }} -->
{{ cards.add_card(title="Printables", content="3D-printable model database; hosts my smaller, printable designs", image="../img/printables.png", url="https://www.printables.com/social/511131-jonspaceharper/about") }}
{{ cards.end_grid() }}

## Contact

How to reach me.

{% import 'assets/macros/cards.md' as cards with context %}
{{ cards.start_grid(3) }}
{{ cards.add_card(title="LinkedIn", content="", image="../img/linkedin.png", url="https://linkedin.com/in/jonspaceharper") }}
{{ cards.add_card(title="Reddit", content="", image="../img/reddit.png", url="https://www.reddit.com/user/jonspaceharper") }}
{{ cards.end_grid() }}

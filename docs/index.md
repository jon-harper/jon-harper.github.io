---
title: Overview
summary: Blog landing page.
authors: Jon Harper
date: 2022-06-16
---

![What I May or May Not Look Like](img/doug.png){ data-title="I Kinda Look Like This" data-description="Sorta." width="250px" align="right" }
## About Me

I'm an IT-oriented problem solver. Things I love:

- writing to document and educate;
- teaching and discussing ideas and concepts;
- designing 3D printable, practical solutions;
- developing in C++ and reading about the nuances of the language;
- scripting in Python to simplify tasks;
- the "ah-ha!" of understanding and sharing that feeling with others.

You can find out more on my [about page](about.md). My [contact page](contact.md) also has links to my [LinkedIn bio](https://www.linkedin.com/in/jonspaceharper/) and other professional social media accounts.

## Projects

{% import 'assets/macros/cards.md' as cards with context %}
{{ cards.start_grid(3) }}
{{ cards.add_card(title="OmniBox", content="A modular, 3D-printable electronics case for 3D printers.", image="../img/omnibox_logo.png", url="projects/omnibox/") }}
{{ cards.add_card(title="Clock 3", content="A prototype enclosed 3D printer used as a testbed for new ideas.", image="../img/clock3.png", url="projects/clock3/") }}
{{ cards.add_card(title="The Clockmaker Project", content="Tools and guides for enclosed 3D printing.", image="../img/clockmaker.png", url="projects/clockmaker/") }}
{{ cards.end_grid() }}

You can find other projects on my [GitHub]("https://github.com/jon-harper?tab=repositories") and [Thingiverse](https://www.thingiverse.com/jonspaceharper/designs) profiles.

<!--## Articles

I occasionally put thoughts down about 3D printing, where it is heading, and my projects. You can find the list of articles on the menu to the left, or [follow me on LinkedIn](https://twitter.com/jonspaceharper) for more.

For shorter, rough drafts, follow my [Twitter account](https://twitter.com/jonspaceharper).-->
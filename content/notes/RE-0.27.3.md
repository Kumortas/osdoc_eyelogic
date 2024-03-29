---
layout: osdoc
title: Release notes for 0.27.3
group: notes
permalink: /0.27.3/
show: false
---

OpenSesame 0.27.3 is the third maintenance release in the 0.27 'Frisky Freud' series, and was released on July 9 2013. If you are upgrading from 0.26, please read the [0.27 release notes][].

New features and enhancements:

- French translation, contributed by Romain Monfollet
- Add `screen` parameter to psycho backend settings
- Provide more detailed version information through `modules()`

Bugs fixed:

- Fix many Unicode errors
- Fix variable setting in checkbox form widgets
- Forms respect item/ experiment background and foreground
- Fix a bug where `self` always referred to the first `inline_script` of the experiment
- Allow custom fonts in legacy backend

Windows packaging:

- Use Python 2.7.5
- All dependencies have been updated to most recent version

[0.27 release notes]: /notes/0.27

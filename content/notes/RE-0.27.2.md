---
layout: osdoc
title: Release notes for 0.27.2
group: notes
permalink: /0.27.2/
show: false
---

OpenSesame 0.27.2 is the second maintenance release in the 0.27 'Frisky Freud' series. If you are upgrading from 0.26, please read the [0.27 release notes][].

Important note:
	
- The behavior of variables in inline_script items has changed slightly. Even though this is unlikely to affect existing experiments, you may want to read the notes regarding 'shared variables' [here](/python/about/).

New features and enhancements:

- Support for Android ([link](/getting-opensesame/android/))
- Add `mouse.set_pos()` and `mouse.get_pressed()` functions
- Add new plug-in API ([link](/plug-ins/create/))
- Support Markdown for help files
- Add touch_response plug-in

Bugs fixed:

- Warn when form widgets are too small
- Allow 0 ms timeout in `mouse` objects
- Allow variably defined foreground color in sketchpad
- Expose more variables to variable inspector
- Change name in script tab on name change
- Fix translation issues in Gabor and noise patches
- Allow capitalization changes when renaming items
- Fix many Unicode errors
- Fix a bug that caused editor fonts to be stuck on Arial (Ubuntu 13.04)

Windows packaging:

- Use Python 2.7.4
- All dependencies have been updated to most recent version

[0.27 release notes]: /notes/0.27

---
layout: osdoc
title: Running experiment without the GUI (opensesamerun)
group: Usage
permalink: /opensesamerun/
---

%--
toc:
 mindepth: 2
--%

## About

`opensesamerun` is a simple tool that allows you to execute OpenSesame experiments with a minimal GUI, or directly, by specifying all necessary options via the command line. A minimal GUI will automatically appear if not all command line options have been specified, notably the experiment file, the subject number, and the log file.

%--
code:
 id: LstHelp
 source: help.txt
 syntax: bash
 caption: |
  A list of command-line options for `opensesamerun`.
--%

## Example

Let's say that you want to run the gaze cuing example experiment, for subject #1, and save the log file in your Documents folder (this example assumes Linux, but it works analogously on other platforms):

%--
code:
 id: LstExample
 source: example.txt
 syntax: bash
 caption: |
  You can run an experiment from the command line with `opensesamerun`.
--%

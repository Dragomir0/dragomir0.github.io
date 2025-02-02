---
title: "MotzkinPathSVG"
summary: "SVG image creator based on a given MotzkinPath"
date: "Nov 12 2023"
draft: false
tags:
- C
- Bash
repoUrl: https://github.com/Dragomir0/MotzkinPath
---

In combinatorics, a Motzkin path is a path of length **n** that can be drawn on a grid and that respects the following constraints:

- Only 3 moves are allowed: northeast (1.1), east (1.0) and southeast (1.-1)
- The path must start at point (0,0)
- The path must end at point (n,0)
- The path can never pass under the segment connecting points (0,0) and (n,0)

Leveraged **Bats** for testing and **Makefile** for automation

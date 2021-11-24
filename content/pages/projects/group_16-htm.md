---
content_type: page
parent_title: Projects
parent_uid: 332f2eab-5d2e-3e04-51e5-b212cabc7de3
title: Group 13
uid: 3ea44805-4a81-c281-22f1-1f62c8c8d827
---

Groups: [1]({{< baseurl >}}/pages/projects/group1) | [2]({{< baseurl >}}/pages/projects/group_2) | [3]({{< baseurl >}}/pages/projects/group_3) | [4]({{< baseurl >}}/pages/projects/group_5) | [5]({{< baseurl >}}/pages/projects/group_6) | [6]({{< baseurl >}}/pages/projects/group_7) | [7]({{< baseurl >}}/pages/projects/group_8) | [8]({{< baseurl >}}/pages/projects/group_9) | [9]({{< baseurl >}}/pages/projects/group_10) | [10]({{< baseurl >}}/pages/projects/group_11) | [11]({{< baseurl >}}/pages/projects/group_13-htm) | [12]({{< baseurl >}}/pages/projects/group_14-htm) | 13 | [14]({{< baseurl >}}/pages/projects/group_18-htm) | [15]({{< baseurl >}}/pages/projects/group_19-htm)

Audio-Driven Laser Tetris
-------------------------

By Cameron Lewis and James Sun

Abstract
--------

The purpose of this project is to demonstrate an advanced version of the classic arcade game Tetris. Our version boasts a much more dynamic and random game-play experience than conventional implementations, bringing new meaning to the concept of background music. Users will manipulate the falling objects as in the traditional game, but there will be several twists. The entire game will be driven by music and then projected onto a large screen using a laser raster system. In addition, more detailed game graphics along with other audio-based effects will be displayed on a VGA monitor connected to the FPGA Labkit.

The audio-based elements of the game will operate in the following manner: the drop rate of the game pieces will be controlled by music frequencies and magnitudes. The audio input to the system will be connected to the AC97 audio decoder on the Labkit which will digitize the analog signals and pass them into the FPGA for processing.

The video components will be comprised of two display elements. First will be the high resolution VGA imaging module, which will display the complete Tetris game with scores, settings, and other game errata. Second will be the laser display, which will interface with the core graphics output of the Tetris game by a separate laser controller module - whose job will be to rapidly modulate the output of the laser at appropriate times as to create a low resolution, scanning raster image of the Tetris playing field.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/resources/presentation13))

Report ([PDF]({{< baseurl >}}/resources/project13))

Report Appendix ([PDF]({{< baseurl >}}/resources/appendix13))
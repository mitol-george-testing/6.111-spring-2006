---
content_type: page
parent_title: Projects
parent_uid: 332f2eab-5d2e-3e04-51e5-b212cabc7de3
title: Group 5
uid: 3b862e69-7adf-714d-c58f-a02ac6fd37e3
---

Groups: [1]({{< baseurl >}}/pages/projects/group1) | [2]({{< baseurl >}}/pages/projects/group_2) | [3]({{< baseurl >}}/pages/projects/group_3) | [4]({{< baseurl >}}/pages/projects/group_5) | 5 | [6]({{< baseurl >}}/pages/projects/group_7) | [7]({{< baseurl >}}/pages/projects/group_8) | [8]({{< baseurl >}}/pages/projects/group_9) | [9]({{< baseurl >}}/pages/projects/group_10) | [10]({{< baseurl >}}/pages/projects/group_11) | [11]({{< baseurl >}}/pages/projects/group_13-htm) | [12]({{< baseurl >}}/pages/projects/group_14-htm) | [13]({{< baseurl >}}/pages/projects/group_16-htm) | [14]({{< baseurl >}}/pages/projects/group_18-htm) | [15]({{< baseurl >}}/pages/projects/group_19-htm)

3-D Pong
--------

By Igor Ginsburg

Abstract
--------

3D Pong takes MIT Pong to the next level with a 3D interface. At the heart of the project there is a hardware based 3D renderer. The renderer takes in a 3D model, specifically a sequence of colored triangles in a 3D space, and produces a 2D SVGA image. The view is controlled through a trackball mouse, which specifies rotations, translations and zoom. While the renderer can take in pre-built models stored in on-chip ROM, during gameplay a model of the current board is generated dynamically.

The project contains several high-level modules in addition to the renderer. A track-ball driver connects to the PS/2 interface and provide rotation, translation and zoom inputs, along with a possible lightsource input, to the renderer. A game-logic module provides ball and paddle coordinates to the game-model builder. The game-model builder turns the ball and paddle coordinates into a 3D model of the game field. The 2D image produced by the renderer is buffered in a double-buffer module which interfaces with the labkit SRAM. An SVGA module uses these buffered images to generate monitor outputs.

The renderer is pipelined, and is divided into several submodules. These include a rotator, a translator, a triangle shader, a projector, and a pixel-painter. The rotator module uses matrix multiplication to rotate triangle vertices about the origin. The translator module uses signed subtraction to recenter the points about a new origin. The shader module calculates a vector normal to the triangle's plain, then take a dot product with the light-source vector, in order to calculate the proper color for the entire triangle. The projector module, uses the z-coordinate of each point to rescale the x and y coordinates, based on a given lens focal length. Finally, the pixel painter enumerates the pixels in the interior of the triangle, storing their colors and z-coordinates to the buffer module.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/resources/presentation5))

Report ([PDF]({{< baseurl >}}/resources/project5))

Report Appendix ([PDF]({{< baseurl >}}/resources/appendix4))
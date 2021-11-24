---
content_type: page
parent_title: Projects
parent_uid: 332f2eab-5d2e-3e04-51e5-b212cabc7de3
title: Group 9
uid: adfdd650-b23d-826e-2a98-f527493aba1b
---

Groups: [1]({{< baseurl >}}/pages/projects/group1) | [2]({{< baseurl >}}/pages/projects/group_2) | [3]({{< baseurl >}}/pages/projects/group_3) | [4]({{< baseurl >}}/pages/projects/group_5) | [5]({{< baseurl >}}/pages/projects/group_6) | [6]({{< baseurl >}}/pages/projects/group_7) | [7]({{< baseurl >}}/pages/projects/group_8) | [8]({{< baseurl >}}/pages/projects/group_9) | 9 | [10]({{< baseurl >}}/pages/projects/group_11) | [11]({{< baseurl >}}/pages/projects/group_13-htm) | [12]({{< baseurl >}}/pages/projects/group_14-htm) | [13]({{< baseurl >}}/pages/projects/group_16-htm) | [14]({{< baseurl >}}/pages/projects/group_18-htm) | [15]({{< baseurl >}}/pages/projects/group_19-htm)

A Two-Input Polygraph
---------------------

By Chris Buenrostro, Isaac Rosmarin, Archana Venkataraman

Abstract
--------

In this project we propose to design and implement a 2-input polygraph using the Xilinx Virtex2 FPGA. The two physiological signals that we will focus on are pulse rate and skin conductivity. These inputs were chosen because they are fairly easy to measure and interpret. During times of emotional stress, such as when the subject is forced to lie, his pulse rate increases. Likewise, the subject is more likely to sweat, thus increasing his skin conductivity.

The project will be divided into three portions: the Physiological Sensor Block, the Digital Control Block, and the Display Block. The sensor block will focus on extracting data from the analog sensors used to measure pulse and skin conductivity. It will involve assembling the two sensors needed for the project, interfacing with an analog-to-digital converter (ADC), and storing the results in a Block RAM. The digital control block is the major control unit for the project. Although it will provide for both user interaction and memory access, most of this section will focus on analyzing data from the sensor. Since the subject is asked several control questions which serve as a baseline, the system must be able to identify different types of questions and algorithmically analyze the physiological signals appropriately. The display block will focus on outputting the measurements and the results. Just as conventional polygraphs record the physiological data using pen and paper, we would like to display the sensor outputs and the computer's decision on the monitor. This portion will provide for additional features such as screen capture, so data can be compared visually.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/resources/presentation9))

Report ([PDF]({{< baseurl >}}/resources/project9))

Report Appendix ([PDF]({{< baseurl >}}/resources/appendix9))
---
content_type: page
parent_title: Projects
parent_uid: 332f2eab-5d2e-3e04-51e5-b212cabc7de3
title: Group 15
uid: 08ca57c2-ac27-d35e-12fb-0c544d7f16bc
---

Groups: [1]({{< baseurl >}}/pages/projects/group1) | [2]({{< baseurl >}}/pages/projects/group_2) | [3]({{< baseurl >}}/pages/projects/group_3) | [4]({{< baseurl >}}/pages/projects/group_5) | [5]({{< baseurl >}}/pages/projects/group_6) | [6]({{< baseurl >}}/pages/projects/group_7) | [7]({{< baseurl >}}/pages/projects/group_8) | [8]({{< baseurl >}}/pages/projects/group_9) | [9]({{< baseurl >}}/pages/projects/group_10) | [10]({{< baseurl >}}/pages/projects/group_11) | [11]({{< baseurl >}}/pages/projects/group_13-htm) | [12]({{< baseurl >}}/pages/projects/group_14-htm) | [13]({{< baseurl >}}/pages/projects/group_16-htm) | [14]({{< baseurl >}}/pages/projects/group_18-htm) | 15

Local Decoding of Walsh Codes to Reduce CDMA Despreading Computation
--------------------------------------------------------------------

By Matthew Doherty

Abstract
--------

Chan et al. invented several novel classes of algorithms to reduce computation in software implementations of the IS-95 reverse link by exploiting software's inherent flexibility over hardware. The algorithms work by processing only a fraction of the despread signal to decode Walsh codewords, relying on an outer feedback loop to choose the fraction of despread signal to process in order to maintain a target bit error rate. Because FPGAs are significantly more flexible than ASICs, the same algorithms can be implemented in an FPGA to reduce computation in hardware. This reduction in computation results directly in power savings because FPGA power consumption is heavily dependent on its gates' switching activity. We propose to implement the "novel and elegant" Generalized Local Decoding of Walsh codewords in an FPGA to determine the potential power savings of the algorithm in hardware.

In doing so, despread codewords from a test data set are processed by the Walsh decoder. Their output bit streams are checked against the known optimal decoding and the bit error rate is determined. This bit error rate is fed back to the decoder, which uses it to choose the fraction of the despread signal to process.

To validate the results, the test data set can be chosen from several of varying signal-to-noise ratio (SNR). In addition, the outer feedback loop can be turned off, so the corresponding bit error rate of the open loop system can be analyzed.

The results are shown in real time on the LCD display, simultaneously comparing the bit error rates and power usages of the optimal decoder, feedback-controlled suboptimal decoder, and open loop suboptimal decoder. Each codeword is processed slowly enough so that it is apparent that the feedback loop is keeping the bit error rate constant and using minimal power.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/resources/presentation15))

Report ([PDF]({{< baseurl >}}/resources/project15))

Report Appendix ([PDF]({{< baseurl >}}/resources/appendix15))
---
title: "Annotating Covert Hazardous Driving Scenarios Online: Utilizing Drivers' Electroencephalography (EEG) Signals"
category: Neuroscience for AI
createdAt: '2023-04-04T14:07'
coverImg: /images/hci_eeg_3.png
heroImg: /images/hci_eeg_1.png
tags: [Hazard Detection, EEG, Annotation, Neuroscience for AI]
author:
  name: Chen Zheng, Muxiao Zi, Wenjie Jiang, Mengdi Chu, Yan Zhang, Jirui Yuan, Guyue Zhou and Jiangtao Gong
---
As autonomous driving systems prevail, it is becoming increasingly critical that the systems learn from
databases containing fine-grained driving scenarios. Most databases currently available are  human-annotated; they are expensive, time-consuming, and subject to behavioral biases. In this paper, we provide initial evidence supporting a novel technique utilizing drivers’ electroencephalography (EEG) signals to implicitly label hazardous driving scenarios while passively viewing recordings of real-road driving, thus sparing the need for manual annotation and avoiding human annotators’ behavioral biases during explicit report. We conducted an EEG experiment using real-life and animated recordings of driving scenarios and asked participants to report danger explicitly whenever necessary. Behavioral results showed the participants tended to report danger only when overt hazards (e.g., a vehicle or a pedestrian appearing unexpectedly from behind an occlusion) were in view. By contrast, their EEG signals were enhanced at the sight of both an overt hazard and a covert hazard (e.g., an occlusion signalling possible appearance of a vehicle or a pedestrian from behind). Thus, EEG signals were more sensitive to driving hazards than explicit reports. Further, the Time-Series AI (TSAI) successfully classified EEG signals corresponding to overt and covert hazards. We discuss future steps necessary to materialize the technique in real life.

![results](/images/hci_eeg_2.jpg)
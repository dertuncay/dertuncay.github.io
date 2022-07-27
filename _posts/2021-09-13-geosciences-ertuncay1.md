---
title: "Identification of Near-Fault Impulsive Signals and Their Initiation and Termination Positions with Convolutional Neural Networks"
share: false
related: false
last_modified_at: 2022-05-16T19:30:00
categories:
  - Work
tags:
  - article
  - machine learning
  - geosciences
---

Identification of Near-Fault Impulsive Signals and Their Initiation and Termination Positions with Convolutional Neural Networks\\
**Deniz Ertuncay**, Andrea De Lorenzo, Giovanni Costa

---

Ground motions recorded in near-fault regions may contain pulse-like traces in the velocity domain. Their long periodicity can identify such signals with large amplitudes. Impulsive signals can be hazardous for buildings, creating large demands due to their long periods. In this study, a dataset was collected from various data centres. Initially, all the impulsive signals, which are in reality rare, are manually identified. Furthermore, then, synthetic velocity waveforms are created to increase the number of impulsive signals by using the model developed by Mavroeidis and Papageorgiou, and k−2 kinematic modelling. In accordance, a convolutional neural network (CNN) was trained to detect impulsive signals by using these synthetic impulsive signals and ordinary signals. Furthermore, manually labelled impulsive signals are used to detect the initiation and the termination positions of impulsive signals. To do so, the velocity waveform and position and amplitude information of the maximum and minimum points are used. Once the model detects the positions, the period of the pulse is calculated by analysing spectral periods. Although our detection algorithm works relatively worse than three robust algorithms used for benchmarks, it works significantly better in the determination of initiation and termination positions. At this moment, our models understand the features of the impulsive signals and detect their location without using any thresholds or any formulations that are heavily used in previous studies.

---

**Citation**

Ertuncay, D., De Lorenzo, A., & Costa, G. (2021). Identification of Near-Fault Impulsive Signals and Their Initiation and Termination Positions with Convolutional Neural Networks. Geosciences, 11(9), 388.

Bibtex

> @article{ertuncay2021identification,
  title={Identification of Near-Fault Impulsive Signals and Their Initiation and Termination Positions with Convolutional Neural Networks},
  author={Ertuncay, Deniz and De Lorenzo, Andrea and Costa, Giovanni},
  journal={Geosciences},
  volume={11},
  number={9},
  pages={388},
  year={2021},
  publisher={MDPI}
}

The article is available [here](https://www.mdpi.com/2076-3263/11/9/388).\\
Github repository of Identification of Impulsive Signals is [here](https://github.com/Machine-Learning-in-Seismology/CNN-Pulse-Classification).\\
Github reposity of Determination of Initiation and Termination Positions of Impulsive Signals is [here](https://github.com/Machine-Learning-in-Seismology/CNN-Pulse-Start-Stop).\\

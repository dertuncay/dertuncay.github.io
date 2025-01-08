---
title: "Deep learning based earthquake and vehicle detection algorithm"
share: false
related: false
last_modified_at: 2025-01-08T14:43:00
categories:
  - Work
tags:
  - article
  - journal of seismology
  - vehicle detection
---

Deep learning based earthquake and vehicle detection algorithm\\
**Deniz Ertuncay**, Andrea de Lorenzo, Giovanni Costa\\

---

Seismic recorders register vibrations from all possible sources. Even though the purpose of the seismic instrument is, usually, to record ground motions coming from tectonic sources, other sources such as vehicles can be recorded. In this study, a machine learning model is developed by using a convolutional neural network (CNN) to separate three different classes which are earthquakes, vehicles, and other noises. To do that vehicle signals from various accelerometric stations from Italy are visually detected. Together with the vehicle signals noise and earthquake information coming from Italy are used. Inputs of the database are 10 s long seismic traces along with their frequency content from three channels of the seismic recorder. CNN model has an accuracy rate of more than 99 % for all classes. To understand the capabilities of the model, seismic traces with vehicles and earthquakes are given as input to the model which the model successfully separates different classes. In the case of the superposition of an earthquake and a vehicle, the model prediction is in favor of the earthquake. Moreover, earthquake signals from various databases are predicted with more than 90 % accuracy.
---

**Citation** 

> Ertuncay, D., de Lorenzo, A. & Costa, G. Deep learning based earthquake and vehicle detection algorithm. J Seismol (2024). https://doi.org/10.1007/s10950-024-10267-8

**Bibtex** 

> @article{ertuncay2024deep,
  title={Deep learning based earthquake and vehicle detection algorithm},
  author={Ertuncay, Deniz and de Lorenzo, Andrea and Costa, Giovanni},
  journal={Journal of Seismology},
  pages={1--13},
  year={2024},
  publisher={Springer}
}

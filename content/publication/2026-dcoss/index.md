---
title: "PoHAR: Understanding Hyperlocal Human Activities with Pollution Sensor Networks"
date: 2026-06-01
publishDate: 
authors: ["**Prasenjit Karmakar**", "Karthik Reddy", "Sandip Chakraborty"]
publication_types: ["1"]
abstract: "Low-cost air quality sensors are becoming ubiquitous in our daily lives as public awareness of air pollution continues to grow, and people take measures to monitor and improve the air they breathe indoors. Besides the standard operation of these sensors, fluctuations in environmental parameters can be leveraged to understand human behavior and activities in indoor spaces. Unlike traditional audio-visual, Radio Frequency, and inertial sensors, air quality sensors are easily scalable to a household, are privacy-preserving, and more economical. Such distributed sensor networks must jointly make decisions to monitor indoor occupants for downstream smart home and healthcare applications. However, due to low processing power, memory, and energy, they often struggle to maintain distributed data consensus and identify activity-affected sensor groups for accurate on-device inference. In this paper, we propose PoHAR framework that implements: (i) a conflict-free replicated data primitive for data sharing, (ii) a hierarchical clustering for ESP32 to detect activity-affected sensor groups with a self-supervised distance metric, and (iii) a leader-based group inference with off-the-shelf ML classifiers, enabling the sensor network to collaboratively detect hyperlocal indoor activities. Our extensive experiments demonstrated on-device activity detection, achieving 97.41% accuracy for indoor activity and 99.68% for cooking activity, using off-the-shelf ML models with latency below 34 microseconds."
featured: true
publication: "IEEE DCOSS-IoT 2026"
links:
  - icon_pack: fas
    icon: scroll
    name: Paper
    url: 'https://arxiv.org/abs/2605.09434'
  # - icon_pack: fas
  #   icon: newspaper
  #   name: Demo Video
  #   url: ''
---
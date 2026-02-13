---
title: "Exploiting Multi-modal Contextual Sensing for City-bus's Stay Location Characterization: Towards Sub-60 Seconds Accurate Arrival Time Prediction"
date: 2023-02-23
publishDate: 2023-02-23
authors: ["Ratna Mandal", "**Prasenjit Karmakar**", "Soumyajit Chatterjee", "Debaleen Das Spandan", "Shouvit Pradhan", "Sujoy Saha", "Sandip Chakraborty", "Subrata Nandi"]
publication_types: ["2"]
abstract: "Intelligent city transportation systems are one of the core infrastructures of a smart city. The true ingenuity of such an infrastructure lies in providing the commuters with real-time information about citywide transport like public buses, allowing them to pre-plan their travel. However, providing prior information for transportation systems like public buses in real-time is inherently challenging because of the diverse nature of different stay-locations where a public bus stops. Although straightforward factors like stay duration extracted from unimodal sources like GPS at these locations look erratic, a thorough analysis of public bus GPS trails for 1,335.365 km at the city of Durgapur, a semi-urban city in India, reveals that several other fine-grained contextual features can characterize these locations accurately. Accordingly, we develop BuStop, a system for extracting and characterizing the stay-locations from multi-modal sensing using commuters’ smartphones. Using this multi-modal information BuStop extracts a set of granular contextual features that allows the system to differentiate among the different stay-location types. A thorough analysis of BuStop using the collected in-house dataset indicates that the system works with high accuracy in identifying different stay-locations such as regular bus stops, random ad hoc stops, stops due to traffic congestion, stops at traffic signals, and stops at sharp turns. Additionally, we develop a proof-of-concept setup on top of BuStop to analyze the potential of the framework in predicting expected arrival time, a critical piece of information required to pre-plan travel at any given bus stop. Subsequent analysis of the PoC framework, through simulation over the test dataset, shows that characterizing the stay-locations indeed helps make more accurate arrival time predictions with deviations less than 60 seconds from the ground-truth arrival time."
featured: true
publication: "ACM Transactions on Internet of Things, Vol. 4, No. 1"
links:
  - icon_pack: fas
    icon: scroll
    name: Paper
    url: 'https://doi.org/10.1145/3549548'
  - icon_pack: fab
    icon: github
    name: Repository
    url: 'https://github.com/prasenjit52282/BuStop'
  - icon_pack: ai
    icon: open-data
    name: Open data
    url: 'https://github.com/stilllearningsoumya/bus_trajectory_dataset'
---
---
title: "What is that Building?: An End-to-end System for Building Recognition from Streetside Images"
collection: publications
permalink: /publication/2020-08-23-building-recognition
excerpt: 'Streetside Building Search-Retrieve System'
date: 2020-08-23
venue: '26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining'
paperurl: 'https://doi.org/10.1145/3394486.3403292'
---
The paper describes Streetside Building Search-Retrieve System (SBSRS) - a system for recognizing buildings from steetside images. SBSRS powers several distinct applications: 1) it improves map-search by enriching its streetview service with semantic information, such as location, business name, open hours, etc.; 2) it enables search by image and location - a novel form of visual image search where both visual and location signals are used to identify the most relevant result to a query image of a building.

SBSRS works in an entirely unsupervised way. It has an offline component, which generates an index of building objects by scraping streetview images, segmenting and conflating them with business information. An online component can then search over the index, utilizing location information to retrieve a small set of geo-relevant results, which are then re-ranked using novel highly accurate visual descriptors. To evaluate the system, we generate a dataset of over 23K unique business buildings from four major US cities. This significantly exceeds the number of landmarks in datasets previously used by similar systems. We compare our system with a state-of-the-art baseline and show its accuracy on our new buildings dataset as well as on two popular landmark datasets.

[Download paper here](https://dl.acm.org/doi/abs/10.1145/3394486.3403292)

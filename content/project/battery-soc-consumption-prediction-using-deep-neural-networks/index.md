---
title: Battery SoC Consumption Prediction Using Deep Neural Networks
date: 2022-02-14T17:43:34.014Z
draft: false
featured: false
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
This is a side project from a funded research. For details, please check:[ Development: The Next-Generation Public Charging Infrastructure and Cyber-Information Network for Enhanced Inclusion and Independent Living of Power Mobility Device Users](https://ece.ncsu.edu/funded-research/development-the-next-generation-public-charging-infrastructure-and-cyber-information-network-for-enhanced-inclusion-and-independent-living-of-power-mobility-device-users/).

**Background:** 1.7 million Americans rely on Power Mobility Devices (PMDs) – power wheelchairs and electric scooters – to improve their mobility. However, they still travel less than users of manual wheelchairs and much less than people without disability, where sometimes only 2% of that distance occurs outdoors. Users and caregivers consistently report the energy constraints of PMD’s batteries as one of the top reasons for limited away-from-home mobility. A collaborative research team from NCSU (Raleigh) and UNC (Chapel Hill) are partnering with a group of stakeholders to pilot a public charging infrastructure and cyber-information system to support outdoor use of power mobility devices, to improve the mobility and inclusion of their owners.

We use the output signal of wheelchair sensors (including IMU, battery, GPS, etc) as input to predict the consumption of the SoC. The prototype prediction model is a simple deep neural network, which is trained in a data-driven way. Experimental results shows that the model is able to predict the consumption of SoC at a good prediction accuracy and real-time inference speed.
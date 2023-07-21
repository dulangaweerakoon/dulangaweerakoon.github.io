---
title: "COSM2IC: Optimizing Real-Time Multi-Modal Instruction Comprehension"
collection: publications
permalink: /publication/cosm2ic
excerpt: ''
date: 28.07.2022
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 
citation: 'Weerakoon, D., Subbaraju, V., Tran, T. and Misra, A., 2022. Cosm2ic: Optimizing real-time multi-modal instruction comprehension. IEEE Robotics and Automation Letters, 7(4), pp.10697-10704.'
---
Supporting real-time, on-device execution of multimodal referring instruction comprehension models is an important challenge to be tackled in embodied Human-Robot Interaction However, state-of-the-art deep learning models are resourceintensive and unsuitable for real-time execution on embedded devices. While model compression can achieve a reduction in computational resources up to a certain point, further optimizations result in a severe drop in accuracy. To minimize this loss in accuracy, we propose the COSM2IC framework, with a lightweight Task Complexity Predictor, that uses multiple sensor inputs to assess the instructional complexity and thereby dynamically switch between a set of models of varying computational intensity such that computationally less demanding models are invoked whenever possible. To demonstrate the benefits of COSM2IC, we utilize a representative human-robot collaborative “table-top target acquisition” task, to curate a new multimodal instruction dataset where a human issues instructions in a natural manner using a combination of visual, verbal, and gestural (pointing) cues. We show that COSM2IC achieves a 3-fold reduction in comprehension latency when compared to a baseline DNN model while suffering an accuracy loss of only ∼5%. When compared to state-of-the-art model compression methods, COSM2IC is able to achieve a further 30% reduction in latency and energy consumption for a comparable performance.

[Download paper here](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=8621&context=sis_research)

<!-- Recommended citation: Weerakoon, D., Subbaraju, V., Tran, T. and Misra, A., 2022. Cosm2ic: Optimizing real-time multi-modal instruction comprehension. IEEE Robotics and Automation Letters, 7(4), pp.10697-10704. -->
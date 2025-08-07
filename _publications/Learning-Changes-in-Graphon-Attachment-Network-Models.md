---
title: "Learning Changes in Graphon Attachment Network Models"
collection: publications
category: conferences
permalink: /publication/Learning-Changes-in-Graphon-Attachment-Network-Models
excerpt: 'We introduce a novel and flexible model for the dynamic growth of random networks, and address the problem of detecting structural change-points—time points at which the underlying network structure undergoes significant shifts—over time. Leveraging the fact that the expected subgraph counts grow polynomially in time, we develop a new multiple change-point detection method for sequences of such statistics. Theoretical guarantees are established, and simulation studies validate the method’s effectiveness. A real-data application demonstrates its ability to detect changes in previously intractable scenarios.'
date: 2025-07-15
venue: 'International Conference on Machine Learning (ICML)'
paperurl: 'https://icml.cc/virtual/2025/poster/45662'
---

This paper introduces Graphon Attachment Network Models (GAN-M), a novel framework for modeling evolving networks with rich structural dependencies, grounded in graphon theory. GAN-M provides a flexible and interpretable foundation for studying network formation by leveraging graphon functions to define attachment probabilities, thereby combining the strengths of graphons with a temporal perspective. A key contribution of this work is a methodology for learning structural changes in these networks over time. Our approach uses graph counts—frequencies of substructures such as triangles and stars—to capture shifts in network topology. We propose a new statistic designed to learn changes in the resulting piecewise polynomial signals and develop an efficient method for change detection, supported by theoretical guarantees. Numerical experiments demonstrate the effectiveness of our approach across various network settings, highlighting its potential for dynamic network analysis.
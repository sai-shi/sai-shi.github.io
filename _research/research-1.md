---
title: "Transfer Learning in radioactive particle tracking"
excerpt: "Keywords: tranfer learning, few-show learning, zero-shot learning, meta learning, chemical engineering. <br/><img src='/images/placement.png'>"
collection: research
---

In this [paper](https://doi.org/10.1016/j.ces.2021.117190), we show that it is possible to reduce the errors and costs associated with the current RPT modeling practices through the application of Transfer Learning approach based on the availability of different historical RPT calibration data. Two machine learning techniques, SVR and FNN, and several distinct TL strategies were tested and their effectiveness in exploiting historical calibration data was evaluated. 

Our empirical evaluation demonstrated that the historical calibration data collected under various simulated conditions can be exploited through TL when training an RPT model under a new condition. The historical data are particularly useful for the zero-shot scenario where it is not possible to obtain calibration data for the new condition and for the few-shot scenario where it is possible to obtain only a limited number of new calibration data points. Also, our results show that TL is more appropriate when historical calibration data correspond to conditions similar to the current simulated condition. 

[Source Code](https://github.com/sai-shi/Transfer-Learning-of-radioactive-particle-tracking)

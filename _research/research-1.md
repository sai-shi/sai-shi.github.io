---
title: "Resource-efficient radioactive particle tracking using feature selection and trasnfer learning"
excerpt: "Keywords: tranfer learning, few-show learning, zero-shot learning, meta learning, feature selection."
collection: research
---

[Source Code](https://github.com/sai-shi/Transfer-Learning-of-radioactive-particle-tracking)

Research question I: Accurate RPT is challenging and time-consuming because of the need to build a new RPT model and recollect large-scale data each time the conditions change. Can we leverage machine learning techniques to reduce such cost? 

We found that it is possible to reduce the errors and costs associated with the current RPT modeling practices through the application of Transfer Learning approach based on the availability of different historical RPT calibration data. Two machine learning techniques, SVR and FNN, and several distinct TL strategies were tested and their effectiveness in exploiting historical calibration data was evaluated. If small subset of new condition data is provided, few-shot learning algorithms such as meta learning can help generalize the model.

Research question II: Deploying a large number of detectors not only increases experimental costs and complexity but also extends the time required for equipment setup and calibration. Can we determine the optimal placement of detectors using feature selection?

Our approach identifies the minimum number of detectors needed and their optimal placement and analyzes how changes in the reactor's medium properties affect them. We also investigated the effect of detector sizes on the prediction accuracy.


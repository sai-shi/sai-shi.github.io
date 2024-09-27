---
title: "Wireless device fingerprinting using domain adaptation"
excerpt: "Keywords: maximum mean discrepancy, wireless network, domain shift, transfer learning."
collection: research
---

Research question: Wireless environment is very sensitive to time, location, and configuration changes. When such domain shift happens, how can we reuse pre-trained models to enable accurate device fingerprinting in the target domain?

We perform an experimental study on the sensitivity of long-range device fingerprinting to variations in deployment settings. The dataset being used in our study covers a comprehensive set of experimental scenarios, considering both indoor and outdoor environments with varying network deployment settings, such as the distance between the transmitter and the receiver and the configuration of the long-range protocol. Classic transfer learning techniques are utilized to explore the domain shift issue within various scenarios and increase the generalization capabilities of deep learning models. We found that the models perform relatively well when trained and tested under the same deployment settings. However, when trained and tested under different settings, the models fail to maintain their high accuracy and lose their ability to classify devices. Under this more challenging scenario, where source and target domain are significantly different, domain adaptation methods are used and it improves the model performance compared to classic transfer learning techniques. 

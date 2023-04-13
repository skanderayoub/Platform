# A platform for time-series anomaly detection and evaluation using Matlab and Simulink

This platform allows users to evaluate the performance of the detection process according to multiple variables, such as the dataset, preprocessing method, DNN type and architecture, training related hyperparameters, different threshold methods and evaluation metrics. It also has the ability to generate the corresponding detection tools for consequent online detection.

------

##### Prerequisites

- Matlab and Simulink
- Matlab's Deep Learning Toolbox 
- Matlab's Econometrics Toolbox
- Matlab's Image Processing Toolbox

##### Platform content

- 3 datasets from different Cyber-Physical System (CPS) domains, 2 of them generated from Simulink models (UAV and AVS) and one base on a real-world scenario (SwAT).
- Different preprocessing methods (standardizing, rescaling and usage of raw data).
- 2 network types, one for reconstruction and one for prediction.
- Different DNN architectures for each network type and ability to tune some training and network related and hyperparameters.
- 2 different thresholding methods for detection, supervised and unsupervised.
- Offline detection window for both detection methods with visual display of results. 
- The offline detection performance is reported with the traditional statistical metrics for machine learning (recall, precision and F1 score).
- Two Simulink models (one for each DNN type) to simulate the online detection using the supervised thresholding method.

##### Instructions for use of the platform

- Select a dataset.
- According to the selected dataset, choose a scenario or sensor.
- Select a preprocessing method and network type.
- Tune hyperparameters and train the DNN.
- According to the selected dataset, choose the faulty data and proceed with online or offline detection.

On the offline detection window, the anomaly padding, window size and z-range can be changed for the unsupervised detection method and dynamically preview the results.






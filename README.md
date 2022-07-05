# Sociability-Measures-Using-Speech-Classification-
Summer machine learning research project (5/15 - 8/5)

# background
(in progress)
In many social scenarios, microphones from our smartphones can capture speech from many concurrent speakers. Concurrent speaker count[8-10] can be used in many applications from occupancy detection, localization, or as a preliminary step for speech recognition. 


To build a robust on-device concurrent speaker estimation algorithm, the first step is to obtain large number of training data from our target domain (smartphones). Currently, only very small amounts of overlap speech datasets are available, which were not recorded using mobile devices, and were collected in constrained scenarios. So the problem is, large-scale free-living overlapped speech dataset is not available, and the effort of data collection and labelling is too high. One possible solution is to simulate target audio (recorded using mobile devices) from high quality audio recordings. 
However, there are several questions to address before the simulation. Do device differences degrade the performance of the concurrent speaker count? What makes the audios different? Can neural networks differentiate audios recorded from different devices? To answer the questions above, in this poster we: 
reproduced the result of state of the art concurrent speaker count algorithm [10] as baseline
evaluated the baseline model on in-domain and out-of-domain data
visualized the differences between audio recorded from different devices 
explored features that can differentiate audios recorded from different devices
trained a neural network to classify audios recorded from different devices

[8] Chen, Siyuan, et al. "An Investigation of Crowd Speech for Room Occupancy Estimation." INTERSPEECH. 2017.
[9] Khan, Md Abdullah Al Hafiz, Nirmalya Roy, and H. M. Hossain. "Wearable sensor-based location-specific occupancy detection in smart environments." Mobile Information Systems 2018 (2018).
[10]CountNet: Estimating the Number of Concurrent Speakers Using Supervised Learning Speaker Count Estimation

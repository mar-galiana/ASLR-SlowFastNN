#  PROJECT CONCLUSIONS

This project has made significant strides in the field of Sign Language Recognition (SLR) by conducting rigorous experiments and implementing advanced models. The primary focus was on two models: the 3DCNN and the SlowFast Neural Network, with the overarching goal of advancing the accuracy of Sign Language Recognition.

The experimentation encompassed several critical phases, with a primary emphasis on data processing techniques and model optimisation. Various data processing methods were rigorously evaluated, taking into account the critical information’s location during sign interpretation. For each frame of every video sample, face and hand detection techniques were meticulously executed to reconstruct the input data, placing greater importance on these essential features.

The models were meticulously trained using a set of 50 manually selected labels. These labels were chosen not only to represent the most significant words used in daily life but also to mirror the different aspects of sign language.

Approximately 68% of the signs primarily involved hand movements, 16% relied on facial expressions, and the remaining portion pertained to signs necessitating whole-body movements, such as arm and shoulder gestures. Throughout these experiments, noteworthy achievements were attained, with the 3DCNN model achieving an accuracy of 68.25%, and the SlowFast Neural Network reaching 66.23%. 

It’s important to highlight that these accomplishments were realised under challenging constraints, including limited computational resources and memory restrictions.

Looking ahead, the project lays a strong foundation for future work. Further research could involve refining the models by retraining with larger batch sizes and more epochs, exploring ensemble models that combine the strengths of the 3DCNN and SlowFast networks, and applying data augmentation techniques. These future endeavours aim to propel Sign Language Recognition technology even further, fostering inclusivity by providing effective communication tools for individuals with speech and hearing impairments.

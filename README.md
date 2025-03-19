# DeepLearningAlzhimerDiseaseClassification
Abstract—Background: Alzheimer’s disease (AD) is a degenerative neurological brain condition that slowly impairs cognitive function and ultimately results in the loss of individual function. Early prognosis improves the chances of preserving the patient’s level of function and delays the onset of Dementia symptoms. Electroencephalogram (EEG) plays a significant role in diag-nosing patients with AD and offers a non-invasive continuous assessment and biomarkers of the disease progression.

New Method: The EEG data acquired using the EGI 300 Geodesic EEG system is used in this research work. The EEG time-series dataset comprises 4 stages of Alzheimer :Normal Control (NC), Subjective Cognitive Decline (SCD), Mild Cognitive Impairment (MCI) and AD. The transformation of 1-D time-series data to 2- D images without manual feature extraction is applied only on ECG data so far and not on EEG data. This motivated us to present a novel image transformation approach for the efficient diagnosis of AD from the EEG signals. Traditional machine learning algorithms demand feature engineering for achieving better accuracy. EEG signal’s nonlinear and non-stationary nature makes it a challenging task to interpret, examine and extract essential features from the data for classification. Thus, deep learning algorithms help to achieve supremacy in terms of accuracy to train with a huge amount of data without feature engineering. In order to extract deep features from the input images for the purpose of detecting Alzheimer’s stage, the generated images are subsequently fed into Keras pre-trained deep learning models. It is critical to precisely diagnose the intermediate stages of AD to detect it early. Most of the recent research concentrate on the binary classification of Alzheimer’s stages (NC vs AD). Hence, this work aims to perform multi-class classification on the EEG signal transformed into images. Comparison with existing methods: ResNet- 101v2 outperformed all other Keras pre-trained models with a highest accuracy of 98.98%.

Conclusion: Thus, converting EEG time-series data into images and using the resulting images to train Convolutional Neural Networks (CNNs) for classification represents a very promising
approach to Alzheimer’s disease diagnosis.

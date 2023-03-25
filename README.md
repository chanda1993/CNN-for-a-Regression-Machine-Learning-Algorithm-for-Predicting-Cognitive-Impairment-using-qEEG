# CNN-for-a-Regression-Machine-Learning-Algorithm-for-Predicting-Cognitive-Impairment-using-qEEG
Abstract

Purpose: Electroencephalogram (EEG) signals give detailed information on the electrical brain activities occurring in the cerebral cortex. They are used to study brain-related disorders such as mild cognitive impairment (MCI) and Alzheimer’s disease (AD). Brain signals obtained using an EEG machine can be a neurophysiological biomarker for early diagnosis of dementia through quantitative EEG (qEEG) analysis. This paper proposes a machine learning methodology to detect MCI and AD from qEEG time-frequency (TF) images of the subjects in an eyes-closed resting state (ECR). 

Participants and Methods: The dataset consisted of 16,910 TF images from 890 subjects: 269 healthy controls (HC), 356 MCI, and 265 AD. First, EEG signals were transformed into TF images using a Fast Fourier Transform (FFT) containing different event-rated changes of frequency sub-bands preprocessed from the EEGlab toolbox in the MATLAB R2021a environment software. The preprocessed TF images were applied in a convolutional neural network (CNN) with adjusted parameters. For classification, the computed image features were concatenated with age data and went through the feed-forward neural network (FNN). 

Results: The trained models’, HC vs. MCI, HC vs. AD, and HC vs. CASE (MCI + AD), performance metrics were evaluated based on the test dataset of the subjects. The accuracy, sensitivity, and specificity were evaluated: HC vs. MCI was 83%, 93%, and 73%, HC vs. AD was 81%, 80%, and 83%, and HC vs. CASE (MCI + AD) was 88%, 80%, and 90%, respectively. 

Conclusion: The proposed models trained with TF images and age can be used to assist clinicians as a biomarker in detecting cognitively impaired subjects at an early stage in clinical sectors.

Keywords: Neurodegenerative Diseases, Electroencephalography, Supervised Machine Learning, Regression Analysis.

Study framework.

![Fig 1](https://user-images.githubusercontent.com/46183754/227709283-0dced95b-e1f8-43a7-b7fc-5804ca1774a3.jpg)

Abbreviations: CNN, convolutional neural network; FFN, feed-forward neural network; HC, healthy controls; MCI, mild cognitive impairment. 

# Parkinson's Disease Classification using two datasets of preprocessed speech signals

# Datasets 

### Dataset 1

The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals. The original study published the feature extraction methods for general voice disorders.

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The "status" column is set to 0 for healthy and 1 for PD.

*Script for Dataset 1: dataset1_classification.ipynb*

*Dataset name: parkinsons.data*

#### References

Little, M. A., McSharry, P. E., Hunter, E. J., Spielman, J., & Ramig, L. O. (2009). Suitability of dysphonia measurements for telemonitoring of Parkinson's disease. IEEE transactions on bio-medical engineering, 56(4), 1015. https://doi.org/10.1109/TBME.2008.2005954

'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)

### Dataset 2 

This dataset is collected from UCI Machine Learning Repository through the following link: https://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification#

The data used in this study were gathered from 188 patients with PD (107 men and 81 women) with ages ranging from 33 to 87 (65.1 ± 10.9) at the Department of Neurology in  Cerrahpaşa Faculty of Medicine, Istanbul University. The control group consists of 64 healthy individuals (23 men and 41 women) with ages varying between 41 and 82 (61.1 ± 8.9). During the data collection process, the microphone is set to 44.1 KHz and following the physician's examination, the sustained phonation of the vowel /a/ was collected from each subject with three repetitions.

Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment.

Two analyses were conducted for this dataset:

*Script 1 for Dataset 2: dataset2_classification_SMOTE.ipynb*

*Script 2 for Dataset 2: dataset2_classification_FOLD.ipnyb*

*Dataset name: pd_speech_features.csv*

#### References

Sakar, C.O., Serbes, G., Gunduz, A., Tunc, H.C., Nizam, H., Sakar, B.E., Tutuncu, M., Aydin, T., Isenkul, M.E. and Apaydin, H., 2018. A comparative analysis of speech signal processing algorithms for Parkinsonâ€™s disease classification and the use of the tunable Q-factor wavelet transform. Applied Soft Computing, DOI: [Web Link] https://doi.org/10.1016/j.asoc.2018.10.022

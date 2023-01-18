
# Transfer Learning on Small Datasets for Improved Fall Detection

Transfer Learning on Small Datasets for Improved Fall Detection (Sensor-2022): https://www.mdpi.com/1424-8220/23/3/1105

Homepage: [https://jiany-ctrl.github.io/](https://jiany-ctrl.github.io/)


## Abstract
Falls in the elderly are associated with significant morbidity and mortality. While numerous fall detection devices incorporating AI and machine learning algorithms have been developed, no known smartwatch-based system has been used successfully in real-time to detect falls for elderly persons. We have developed and deployed a SmartFall system on a commodity-based smartwatch which has been trialled by nine elderly participants. The system, while being usable and welcomed by the participants in our trials, has two serious limitations. The first limitation is the inability to collect a large amount of personalized data for training. When the fall detection model, which is trained with insufficient data, is used in the real world, it generates a large amount of false positives. The second limitation is the model drift problem. This means an accurate model trained using data collected with a specific device performs sub-par when used in another device. Therefore, building one model for each type of device/watch is not a scalable approach for developing smartwatch-based fall detection system. To tackle those issues, we first collected three datasets including accelerometer data for fall detection problem from different devices: the Microsoft watch (MSBAND), the Huawei watch, and the meta-sensor device. After that, a transfer learning strategy was applied to first explore the use of transfer learning to overcome the small dataset training problem for fall detection. We also demonstrated the use of transfer learning to generalize the model across the heterogeneous devices. Our preliminary experiments demonstrate the effectiveness of transfer learning for improving fall detection, achieving an F1 score higher by over 10% on average, an AUC higher by over 0.15 on average, and a smaller false positive prediction rate than the non-transfer learning approach across various datasets collected using different devices with different hardware specifications.


## Datasets

Huawei Smartwatch Dataset contains the data of 11 volunteers, each volunteer's data contains several ADL (labelled 0) tasks such as walking, washing hands, drinking water, etc..., as well as fall data, specifically 4 different types of falls (front, back, left, right) and 4 falls per type, totalling out to 16 falls per volunteer. The dataset was then split into a 70%/30% Train/Test split and the download link is as follows:

[Huawei smartwatch dataset](https://github.com/jiany-ctrl/Dataset-for-TL-for-fall-detection/blob/main/Huawei_dataset.zip)   


## Citation
If you find this repository useful, please consider citing the following paper:


```
@Article{s23031105,
AUTHOR = {Maray, Nader and Ngu, Anne Hee and Ni, Jianyuan and Debnath, Minakshi and Wang, Lu},
TITLE = {Transfer Learning on Small Datasets for Improved Fall Detection},
JOURNAL = {Sensors},
VOLUME = {23},
YEAR = {2023},
NUMBER = {3},
ARTICLE-NUMBER = {1105},
URL = {https://www.mdpi.com/1424-8220/23/3/1105},
ISSN = {1424-8220},
DOI = {10.3390/s23031105}
}
```





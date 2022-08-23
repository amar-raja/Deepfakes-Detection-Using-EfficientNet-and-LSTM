# Deepfakes-Detection-Using-EfficientNet-and-LSTM

## 1. Introduction
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained EfficientNet CNN is used to obtain a feature vector, further the LSTM layer is trained using the features.

## 2. Our Results

EfficientNetB0
| Dataset | No of videos | Accuracy |
|------------|--------------|--------------|----------|
|Celeb-DF | 1068 | 82.9|
|Face-forensics | 1989 | 89.19|
|DFDC | 3293| 80.1|
|Celeb and FF | 3155| 82.05 |
|All | 6450 | 79.89 |

EfficientNetB1
| Dataset | No of videos | Accuracy |
|------------|--------------|--------------|----------|
|Celeb-DF | 1068 | 85.89|
|Face-forensics | 1989 | 93.46|
|DFDC | 3293| 82.16|
|Celeb and FF | 3155| 85.4 |
|All | 6450 | 86.32 |


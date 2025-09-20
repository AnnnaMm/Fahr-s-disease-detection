## This project aimed to investigate the effectiveness of various CNNs in detecting a rare brain pathology - Fahr's disease, using CT images. As part of the study, a new unique dataset was created, which will soon be available on Kaggle. The research was funded by grant as part of the "Excellence Initiative - Research University" project and in collaboration with my supervisor, Professor of Adam Mickiewicz University in Poznań. 
> * Datasets sourses:
>   - _Kaggle:_ 
>   - _Kaggle:_
> 
> * Used technologies:
>   - Python | Jupyter | VS Code
> * Used libraries:
>   - pandas | numpy | matplotlib | cv2 | random | time | PIL | Tensorflow | Keras | sklearn | splitfolders | os | seaborn | imutils
> * Used models:
>   - VGG19 | DenseNet121 | InceptionV3 | ResNet50 | ResNet50V2 | EfficientNetV2B3 | EfficientNetV2B0 | Xception
## Data
* Fahr's disease:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/fr.jpg)

## Training
### VGG19

* Epoch ≥ 30, optimizer= "adam"

* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/v.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/v.png)


- Accuracy: 100.00%
- Precision: 100.00%
- Recall: 100.00%
- F1-score: 100.00%

### DenseNet121
* Epoch ≥ 15, optimizer= "adam"
  
* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/d.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/d.png)

- Accuracy: 100.00%
- Precision: 100.00%
- Recall: 100.00%
- F1-score: 100.00%

### InceptionV3

* Epoch ≥ 30, optimizer= "sgd"
  
* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/InceptionV3.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/i.png)

- Accuracy: 100.00%
- Precision: 100.00%
- Recall: 100.00%
- F1-score: 100.00%

### ResNet50

* Epoch ≥ 30, optimizer= "adam"
  
* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/r.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/r.png)

- Accuracy: 96.00%
- Precision: 93.75%
- Recall: 100.00%
- F1-score: 96.77%

### ResNet50V2

* Epoch ≥ 30, optimizer= "adam"

* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/rv2.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/RV2.png)

- Accuracy: 96.00%
- Precision: 93.75%
- Recall: 100.00%
- F1-score: 96.77%


### EfficientNetV2B3

* Epoch ≥ 35, optimizer= "adam"


* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/e.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/e.png)

- Accuracy: 60.00%
- Precision: 60.00%
- Recall: 100.00%
- F1-score: 75.00%

### EfficientNetV2B0

* Epoch ≥ 35, optimizer= "adam"

* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/ev2.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/e2.png)

- Accuracy: 92.00%
- Precision: 100.00%
- Recall: 86.67%
- F1-score: 92.86%

### Xception

* Epoch ≥ 15, optimizer= "adam"

* Training process:\
![1](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/eng/x.png)

* ROC:\
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/rcauc/x.png)

- Accuracy: 92.00%
- Precision: 100.00%
- Recall: 86.67%
- F1-score: 92.86%


## Results
T(s) and P(s) are training and prediction times in seconds.
![2](https://github.com/AnnnaMm/Fahr-s-disease-detection/blob/main/results.jpg)


> [!IMPORTANT]
> For full access to the code and additional information, contact the repository owner -> annamamch17@gmail.com .
